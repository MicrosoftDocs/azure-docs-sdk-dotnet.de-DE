<Type Name="Range&lt;T&gt;" FullName="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class Range&lt;T&gt; : IComparable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;, IEquatable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt; where T : IComparable&lt;T&gt;, IEquatable&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Range`1&lt;(class System.IComparable`1&lt;!T&gt;, class System.IEquatable`1&lt;!T&gt;) T&gt; extends System.Object implements class System.IComparable`1&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;&gt;, class System.IEquatable`1&lt;class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt;&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.Range`1" />
  <TypeSignature Language="VB.NET" Value="Public Class Range(Of T)&#xA;Implements IComparable(Of Range(Of T)), IEquatable(Of Range(Of T))" />
  <TypeSignature Language="F#" Value="type Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; = class&#xA;    interface IEquatable&lt;Range&lt;'T&gt;&gt;&#xA;    interface IComparable&lt;Range&lt;'T&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
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
      <InterfaceName>System.IComparable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IEquatable&lt;Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for classes used with IPartitionResolver is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <typeparam name="T">Jeder Typ, der für Bereichsvergleiche verwendet werden kann.</typeparam>
    <summary>
            Eine Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </summary>
    <remarks>
            Unterstützung für Klassen mit IPartitionResolver ist mittlerweile veraltet. Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.
            </remarks>
    <altmember cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" />
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (T point);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T point) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (point As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : 'T -&gt; Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; point" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="point" Type="T" />
      </Parameters>
      <Docs>
        <param name="point">Ein Wert, der verwendet wird, um den Bereich festzulegen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> Klasse für einen einzelnen Wert.
            </summary>
        <remarks>
            Verwenden Sie diesen Konstruktor zum Erstellen eines Partitionierungsschemas für diskrete/ledig-Werte.
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Range (T low, T high);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T low, !T high) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.#ctor(`0,`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (low As T, high As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; : 'T * 'T -&gt; Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt;" Usage="new Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt; (low, high)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="low" Type="T" />
        <Parameter Name="high" Type="T" />
      </Parameters>
      <Docs>
        <param name="low">Der niedrige Wert im Bereich.</param>
        <param name="high">Der hohe Wert im Bereich.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> -Klasse unter Verwendung der angegebenen niedrigen und hohen Werten.
            </summary>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
        <exception cref="T:System.ArgumentException">Löst eine Ausnahme aus, wenn der Bereich ungültig ist (niedrig ist größer als der hohe).</exception>
      </Docs>
    </Member>
    <Member MemberName="CompareTo">
      <MemberSignature Language="C#" Value="public int CompareTo (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int32 CompareTo(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.CompareTo(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function CompareTo (other As Range(Of T)) As Integer" />
      <MemberSignature Language="F#" Value="abstract member CompareTo : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; int&#xA;override this.CompareTo : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; int" Usage="range.CompareTo other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IComparable`1.CompareTo(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other">Der andere Bereich verglichen werden soll.</param>
        <summary>
            Vergleicht zwei Bereiche.
            </summary>
        <returns>Gibt-1 zurück, wenn der Bereich kleiner als der übergebene Bereich von 1, wenn größer ist, und 0, wenn gleich.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Contains(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Contains other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other">Der Eingabebereich überprüft werden soll, wenn sie in diesem Bereich enthalten ist.</param>
        <summary>
            Überprüft, ob der Bereich für einen anderen Bereich enthält...
            </summary>
        <returns>Gibt "true" zurück, wenn der Eingabebereich adressiert, in dem Bereich enthalten ist.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (T point);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(!T point) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Contains(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contains (point As T) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Contains : 'T -&gt; bool" Usage="range.Contains point" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="point" Type="T" />
      </Parameters>
      <Docs>
        <param name="point">Der Schlüssel, wenn Sie im Bereich überprüft werden.</param>
        <summary>
            Überprüft, ob der Bereich für einen Schlüssel enthält.
            </summary>
        <returns>Gibt "true" zurück, wenn der Schlüssel im Bereich liegt.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public bool Equals (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Equals(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Equals(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Equals (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Equals other" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IEquatable`1.Equals(`0)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other">der Eingabebereich adressiert, der mit diesem Bereich verglichen werden.</param>
        <summary>
            Überprüft, ob die beiden Bereiche gleich sind.
            </summary>
        <returns>Gibt True zurück, wenn der Eingabebereich zu diesem Bereich entspricht.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="range.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erstellt den Hashcode für den Bereich an.
            </summary>
        <returns>Gibt den Hashcode für den Bereich zurück.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="High">
      <MemberSignature Language="C#" Value="public T High { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T High" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.Range`1.High" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property High As T" />
      <MemberSignature Language="F#" Value="member this.High : 'T" Usage="Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.High" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Höchstwert des Bereichs ab.
            </summary>
        <value>
            Der hohe Wert im Bereich.
            </value>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Intersect">
      <MemberSignature Language="C#" Value="public bool Intersect (Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt; other);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Intersect(class Microsoft.Azure.Documents.Partitioning.Range`1&lt;!T&gt; other) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.Intersect(Microsoft.Azure.Documents.Partitioning.Range{`0})" />
      <MemberSignature Language="VB.NET" Value="Public Function Intersect (other As Range(Of T)) As Boolean" />
      <MemberSignature Language="F#" Value="member this.Intersect : Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; IComparable&lt;'T&gt; and 'T :&gt; IEquatable&lt;'T&gt;)&gt; -&gt; bool" Usage="range.Intersect other" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="other" Type="Microsoft.Azure.Documents.Partitioning.Range&lt;T&gt;" />
      </Parameters>
      <Docs>
        <param name="other">die Eingabe <see cref="T:Microsoft.Azure.Documents.Partitioning.Range`1" /> mit diesem Bereich verglichen werden soll.</param>
        <summary>
            Überprüft, ob der Bereich <paramref name="other" /> mit diesem Bereich überschneidet.
            </summary>
        <returns>Gibt "true" zurück, wenn die beiden Bereiche einander überschneiden.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Low">
      <MemberSignature Language="C#" Value="public T Low { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Low" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.Range`1.Low" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Low As T" />
      <MemberSignature Language="F#" Value="member this.Low : 'T" Usage="Microsoft.Azure.Documents.Partitioning.Range&lt;'T (requires 'T :&gt; System.IComparable&lt;'T&gt; and 'T :&gt; System.IEquatable&lt;'T&gt;)&gt;.Low" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den niedrigen Wert im Bereich ab.
            </summary>
        <value>
            Der niedrige Wert im Bereich.
            </value>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.Range`1.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="range.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Konvertiert den Bereich in eine Zeichenfolge im Format "Low, high"
            </summary>
        <returns>Gibt eine Zeichenfolgendarstellung des Bereichs zurück.</returns>
        <remarks>
            Range-Klasse, die einen Bereich von verwendeten darstellt, die <see cref="T:Microsoft.Azure.Documents.Partitioning.RangePartitionResolver`1" /> Klasse im Azure-Cosmos-DB-Dienst.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>