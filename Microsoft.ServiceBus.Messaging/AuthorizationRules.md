<Type Name="AuthorizationRules" FullName="Microsoft.ServiceBus.Messaging.AuthorizationRules">
  <TypeSignature Language="C#" Value="public class AuthorizationRules : System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AuthorizationRules extends System.Object implements class System.Collections.Generic.ICollection`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;, class System.Collections.IEnumerable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationRules&#xA;Implements ICollection(Of AuthorizationRule), IEnumerable(Of AuthorizationRule)" />
  <TypeSignature Language="F#" Value="type AuthorizationRules = class&#xA;    interface ICollection&lt;AuthorizationRule&gt;&#xA;    interface seq&lt;AuthorizationRule&gt;&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.CollectionDataContract(ItemName="AuthorizationRule", Name="AuthorizationRules", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(Microsoft.ServiceBus.Messaging.AuthorizationRule))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt eine Auflistung von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" />.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationRules (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; enumerable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; enumerable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.#ctor(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AuthorizationRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (enumerable As IEnumerable(Of AuthorizationRule))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.AuthorizationRules : seq&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; -&gt; Microsoft.ServiceBus.Messaging.AuthorizationRules" Usage="new Microsoft.ServiceBus.Messaging.AuthorizationRules enumerable" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enumerable" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerable">Die Liste der <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" />.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> Klasse mit einer Liste von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" />.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.ServiceBus.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Add(class Microsoft.ServiceBus.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.Add(Microsoft.ServiceBus.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Add (item As AuthorizationRule)" />
      <MemberSignature Language="F#" Value="abstract member Add : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; unit&#xA;override this.Add : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; unit" Usage="authorizationRules.Add item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Add(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.ServiceBus.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">Die hinzuzufügende <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" />-Instanz.</param>
        <summary>Fügt das angegebene <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> in der Auflistung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="abstract member Clear : unit -&gt; unit&#xA;override this.Clear : unit -&gt; unit" Usage="authorizationRules.Clear " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Clear</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Löscht alle Elemente in der Auflistung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.ServiceBus.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contains(class Microsoft.ServiceBus.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.Contains(Microsoft.ServiceBus.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (item As AuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contains : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; bool&#xA;override this.Contains : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; bool" Usage="authorizationRules.Contains item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Contains(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.ServiceBus.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">Das Element in der Auflistung gesucht werden soll.</param>
        <summary>Bestimmt, ob das angegebene Element in der Auflistung vorhanden ist.</summary>
        <returns>"true", wenn das angegebene Element gefunden wird; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyTo">
      <MemberSignature Language="C#" Value="public void CopyTo (Microsoft.ServiceBus.Messaging.AuthorizationRule[] array, int arrayIndex);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void CopyTo(class Microsoft.ServiceBus.Messaging.AuthorizationRule[] array, int32 arrayIndex) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.CopyTo(Microsoft.ServiceBus.Messaging.AuthorizationRule[],System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyTo (array As AuthorizationRule(), arrayIndex As Integer)" />
      <MemberSignature Language="F#" Value="abstract member CopyTo : Microsoft.ServiceBus.Messaging.AuthorizationRule[] * int -&gt; unit&#xA;override this.CopyTo : Microsoft.ServiceBus.Messaging.AuthorizationRule[] * int -&gt; unit" Usage="authorizationRules.CopyTo (array, arrayIndex)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="array" Type="Microsoft.ServiceBus.Messaging.AuthorizationRule[]" />
        <Parameter Name="arrayIndex" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="array">Das Array zum Speichern der kopierten Elemente.</param>
        <param name="arrayIndex">Der nullbasierte Index, an dem Kopieren begonnen wird.</param>
        <summary>Kopiert die Elemente in ein Array, beginnend am angegebenen Arrayindex begonnen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public int Count { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.AuthorizationRules.Count" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Count As Integer" />
      <MemberSignature Language="F#" Value="member this.Count : int" Usage="Microsoft.ServiceBus.Messaging.AuthorizationRules.Count" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.Count</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Anzahl der <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> in der Auflistung enthalten.</summary>
        <value>Die Anzahl der <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> in der Auflistung enthalten.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetEnumerator () As IEnumerator(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft einen Enumerator, der Durchlaufen der Auflistung ab.</summary>
        <returns>Der Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetRules (Predicate&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; match);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.List`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetRules(class System.Predicate`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; match) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.GetRules(System.Predicate{Microsoft.ServiceBus.Messaging.AuthorizationRule})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (match As Predicate(Of AuthorizationRule)) As List(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="member this.GetRules : Predicate&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; -&gt; System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetRules match" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="match" Type="System.Predicate&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" />
      </Parameters>
      <Docs>
        <param name="match">Die Autorisierungsregel mit dem angegebenen Wert übereinstimmt.</param>
        <summary>Ruft die Sätze von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" />.</summary>
        <returns>Die Sätze von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> , die den angegebenen Wert entsprechen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetRules (string claimValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.List`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; GetRules(string claimValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.GetRules(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRules (claimValue As String) As List(Of AuthorizationRule)" />
      <MemberSignature Language="F#" Value="member this.GetRules : string -&gt; System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" Usage="authorizationRules.GetRules claimValue" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="claimValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="claimValue">Der zu suchende Wert.</param>
        <summary>Ruft den Satz von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> , die mit den angegebenen Wert übereinstimmt.</summary>
        <returns>Die Sätze von <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> , die den angegebenen Wert entsprechen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasEqualRuntimeBehavior">
      <MemberSignature Language="C#" Value="public bool HasEqualRuntimeBehavior (Microsoft.ServiceBus.Messaging.AuthorizationRules comparand);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool HasEqualRuntimeBehavior(class Microsoft.ServiceBus.Messaging.AuthorizationRules comparand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.HasEqualRuntimeBehavior(Microsoft.ServiceBus.Messaging.AuthorizationRules)" />
      <MemberSignature Language="VB.NET" Value="Public Function HasEqualRuntimeBehavior (comparand As AuthorizationRules) As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasEqualRuntimeBehavior : Microsoft.ServiceBus.Messaging.AuthorizationRules -&gt; bool" Usage="authorizationRules.HasEqualRuntimeBehavior comparand" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="comparand" Type="Microsoft.ServiceBus.Messaging.AuthorizationRules" />
      </Parameters>
      <Docs>
        <param name="comparand">Die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> , mit dem aktuellen Objekt verglichen werden soll.</param>
        <summary>Bestimmt, ob das angegebene <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> hat als das aktuelle Objekt gleich Laufzeitverhalten.</summary>
        <returns>"true", wenn das Laufzeitverhalten gleich sind; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="innerCollection">
      <MemberSignature Language="C#" Value="public readonly System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; innerCollection;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Collections.Generic.ICollection`1&lt;class Microsoft.ServiceBus.Messaging.AuthorizationRule&gt; innerCollection" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.AuthorizationRules.innerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly innerCollection As ICollection(Of AuthorizationRule) " />
      <MemberSignature Language="F#" Value="val mutable innerCollection : System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;" Usage="Microsoft.ServiceBus.Messaging.AuthorizationRules.innerCollection" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ICollection&lt;Microsoft.ServiceBus.Messaging.AuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt die Beschreibung der eingeschlossenen Sammlung.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsReadOnly">
      <MemberSignature Language="C#" Value="public bool IsReadOnly { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsReadOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.AuthorizationRules.IsReadOnly" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsReadOnly As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsReadOnly : bool" Usage="Microsoft.ServiceBus.Messaging.AuthorizationRules.IsReadOnly" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Collections.Generic.ICollection`1.IsReadOnly</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt sie fest, ob die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ist schreibgeschützt.</summary>
        <value>True, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> gelesen wird, nur wurde, andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.ServiceBus.Messaging.AuthorizationRule item);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Remove(class Microsoft.ServiceBus.Messaging.AuthorizationRule item) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.Remove(Microsoft.ServiceBus.Messaging.AuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="Public Function Remove (item As AuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; bool&#xA;override this.Remove : Microsoft.ServiceBus.Messaging.AuthorizationRule -&gt; bool" Usage="authorizationRules.Remove item" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.ICollection`1.Remove(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="item" Type="Microsoft.ServiceBus.Messaging.AuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="item">Das zu entfernende Element.</param>
        <summary>Entfernt den angegebenen <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRule" /> aus der Auflistung.</summary>
        <returns>"true", wenn der Vorgang erfolgreich war; andernfalls "false".</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequiresEncryption">
      <MemberSignature Language="C#" Value="public bool RequiresEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RequiresEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.AuthorizationRules.RequiresEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequiresEncryption As Boolean" />
      <MemberSignature Language="F#" Value="member this.RequiresEncryption : bool" Usage="Microsoft.ServiceBus.Messaging.AuthorizationRules.RequiresEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft einen Wert, der angibt, ob die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> Verschlüsselung erfordert.</summary>
        <value>True, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> Verschlüsselung erfordert, andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.AuthorizationRules.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Messaging.AuthorizationRules.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt das Serialisierungsprogramm zum Serialisieren und Deserialisieren des Objekts an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Ruft einen Enumerator, der Durchlaufen der Auflistung ab.</summary>
        <returns>Der Enumerator, der zum Durchlaufen der Auflistung verwendet werden kann.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetSharedAccessAuthorizationRule">
      <MemberSignature Language="C#" Value="public bool TryGetSharedAccessAuthorizationRule (string keyName, out Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule rule);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryGetSharedAccessAuthorizationRule(string keyName, [out] class Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule&amp; rule) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.AuthorizationRules.TryGetSharedAccessAuthorizationRule(System.String,Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryGetSharedAccessAuthorizationRule (keyName As String, ByRef rule As SharedAccessAuthorizationRule) As Boolean" />
      <MemberSignature Language="F#" Value="member this.TryGetSharedAccessAuthorizationRule : string *  -&gt; bool" Usage="authorizationRules.TryGetSharedAccessAuthorizationRule (keyName, rule)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rule" Type="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Name des Schlüssels.</param>
        <param name="rule">Die Regel, die dem angegebenen Schlüssel zugeordnet wird.</param>
        <summary>Ruft die dem angegebenen Schlüssel zugeordnete Regel ab.</summary>
        <returns>True, wenn die <see cref="T:Microsoft.ServiceBus.Messaging.AuthorizationRules" /> ein Element mit dem angegebenen Schlüssel enthält, andernfalls false.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>