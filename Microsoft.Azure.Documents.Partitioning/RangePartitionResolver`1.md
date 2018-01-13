<Type Name="RangePartitionResolver&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class RangePartitionResolver&lt;T&gt; : Microsoft.Azure.Documents.Client.IPartitionResolver where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RangePartitionResolver`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  <TypeSignature Language="VB.NET" Value="Public Class RangePartitionResolver(Of T)&#xA;Implements IPartitionResolver" />
  <TypeSignature Language="F#" Value="type RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IPartitionResolver" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <InterfaceName>System.IComparable&lt;T&gt;</InterfaceName>
        <InterfaceName>System.IEquatable&lt;T&gt;</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">Der Typ des Werts für die Bereichspartitionierung verwendet werden soll.</typeparam>
    <summary>
            RangePartitionResolver implementiert Partitionierung im Azure-Cosmos-DB-Dienst mithilfe einer partitionszuordnung von Wertebereichen für eine Sammlung, die Self-link.
            Dies funktioniert gut, wenn die Daten natürlich geordnete und häufig abgefragt ab Wertebereiche, z. B. für zeitreihendaten oder alphabetische Bereiche von Zeichenfolgen verwenden.
            </summary>
    <remarks>
      <para>
            Unterstützung für IPartitionResolver-basierten Klassen ist mittlerweile veraltet. Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.
            </para>
      <para>
            In einer Bereichspartitionierung werden Partitionen basierend darauf zugewiesen, ob der Partitionsschlüssel in einem bestimmten Bereich liegt. Die RangePartitionResolver-Klasse können Sie die Verwalten einer Zuordnung zwischen einer <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> und Self-link-Auflistung.
            </para>
      <para>
        <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" />ist eine einfache Klasse zum Angeben von Bereichen von Typen, die implementieren <see cref="T:System.IComparable`1" /> und <see cref="T:System.IEquatable`1" /> wie Zeichenfolgen oder Zahlen. Für liest und erstellt, Sie können in jeder beliebigen Bereich übergeben, und der Konfliktlöser identifiziert alle möglichen Sammlungen durch Identifizieren der Bereiche der Partitionen, die Twith angeforderten Bereich überschneidet.
            </para>
      <para>
            Ein spezieller Fall der Bereichspartitionierung ist, wenn der Bereich nur einen einzelnen diskreten Wert bezeichnet Suche Partitionierung ist. Dies wird häufig für die Partitionierung von diskreten Werten wie Region oder Typ oder zur Partitionierung von Mandanten in einer mehrinstanzenfähigen Anwendung verwendet.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (Func&lt;object,object&gt; partitionKeyExtractor, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, object&gt; partitionKeyExtractor, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.Func{System.Object,System.Object},System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, Object), partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : Func&lt;obj, obj&gt; * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyExtractor, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.Object&gt;" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</param>
        <param name="partitionMap">Eine Karte aus dem Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyExtractor" /> Wert.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn einer der Parameter null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RangePartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; partitionMap);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; partitionMap) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.#ctor(System.String,System.Collections.Generic.IDictionary{Microsoft.Azure.Documents.Partitioning.Range{`0},System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, partitionMap As IDictionary(Of Range(Of T), String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : string * System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt; -&gt; Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (partitionKeyPropertyName, partitionMap)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="partitionMap" Type="System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</param>
        <param name="partitionMap">Eine Karte aus dem Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse in der Azure-Cosmos-DB-Dienst unter Verwendung des angegebenen <paramref name="partitionKeyPropertyName" /> Wert.
            </summary>
        <remarks>
            Wird verwendet, wenn Sie basierend auf einem einzelnen Eigenschaftennamen partitionieren möchten. Verwenden Sie den Konstruktor für andere Partitionierungsschemas stattdessen mit PartitionKeyExtractor fest.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn einer der Parameter null ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="rangePartitionResolver.GetPartitionKey document" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.GetPartitionKey(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="document" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="document">Ein Document-Objekt</param>
        <summary>
            Extrahiert den Partitionsschlüssel aus dem angegebenen Dokument mit dem angegebenen <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" /> Eigenschaft oder <see cref="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" /> Funktion Präferenz im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Objekt, das als Partitionsschlüssel verwendet.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn dies nicht möglich, zum Extrahieren des Schlüssels für die Partition.</exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,object&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, object&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, Object)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, obj&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Funktion zum Extrahieren des partitionsschlüssels aller Objekte in der Azure-Cosmos-DB-Dienst ab.
            </summary>
        <value>
            Die Funktion, die den Partitionsschlüssel aller Objekte zu extrahieren.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionKeyPropertyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Name der Eigenschaft in das Dokument das hashing im Azure-Cosmos-DB-Dienst ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionMap">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,string&gt; PartitionMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;, string&gt; PartitionMap" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.PartitionMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionMap As IDictionary(Of Range(Of T), String)" />
      <MemberSignature Language="F#" Value="member this.PartitionMap : System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;'T&gt;, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.RangePartitionResolver&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.PartitionMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zuordnung von Bereich Auflistung-Link, der für die Partitionierung Anforderungen in der Azure-Cosmos-DB-Dienst verwendet wird.
            </summary>
        <value>
            Die Zuordnung von Bereich Sammlung verknüpfen, die für die Partitionierung von Anforderungen verwendet wird.
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="rangePartitionResolver.ResolveForCreate partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForCreate(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Der Partitionsschlüssel verwendet werden, um zu bestimmen, die Zielsammlung für erstellen</param>
        <summary>
            Erhält eine Partition drücken, gibt die richtigen Auflistung Self-link für das Erstellen eines Dokuments mithilfe der partitionszuordnung Bereich im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Den Link der Ziel-Auflistung, der zum Erstellen von Dokumenten verwendet werden.</returns>
        <remarks>
            Wenn mehrere Bereiche der angegebenen partitionkey-Werte übereinstimmen, gibt der Konfliktlöser der übereinstimmenden Bereiche zurück. Wenn keiner der Bereiche entspricht, löst die Methode eine <see cref="T:System.InvalidOperationException" />. Wenn PartitionKey null ist, werden alle Sammlungen zurückgegeben.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn <paramref name="partitionKey" /> ist null.</exception>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn die <paramref name="partitionKey" /> ist ein ungültiger Typ oder keiner der Bereiche auf den angegebenen Partitionsschlüssel entspricht.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="rangePartitionResolver.ResolveForRead partitionKey" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Documents.Client.IPartitionResolver.ResolveForRead(System.Object)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Der Partitionsschlüssel verwendet, um die Zielsammlungen für die Abfrage zu ermitteln.</param>
        <summary>
            Erhält eine Partition drücken, gibt eine Liste der Sammlung von Links zum Lesen aus der Verwendung der partitionszuordnung Bereich im Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Die Liste der zielverknüpfungen-Auflistung.</returns>
        <remarks>
            Die <paramref name="partitionKey" /> muss eine Instanz von <typeparamref name="T" />, <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> oder ein <see cref="T:System.Collections.Generic.IEnumerable`1" />. " /&gt;. Diese Methode gibt alle Sammlungen, die Bereiche, die mit dem angegebenen intersect entspricht <paramref name="partitionKey" />.
            </remarks>
        <exception cref="T:System.InvalidOperationException">
            Wird ausgelöst, wenn die <paramref name="partitionKey" /> ist ein ungültiger Typ.
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>