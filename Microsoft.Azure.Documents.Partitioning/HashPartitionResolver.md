<Type Name="HashPartitionResolver" FullName="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver">
  <TypeSignature Language="C#" Value="public class HashPartitionResolver : IDisposable, Microsoft.Azure.Documents.Client.IPartitionResolver" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HashPartitionResolver extends System.Object implements class Microsoft.Azure.Documents.Client.IPartitionResolver, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" />
  <TypeSignature Language="VB.NET" Value="Public Class HashPartitionResolver&#xA;Implements IDisposable, IPartitionResolver" />
  <TypeSignature Language="F#" Value="type HashPartitionResolver = class&#xA;    interface IPartitionResolver&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Client.IPartitionResolver</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for IPartitionResolver based classes is now obsolete. It's recommended that you use partitioned collections for higher storage and throughput.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            HashPartitionResolver implementiert Partitionierung anhand des Werts einer Hashfunktion, sodass Sie Anforderungen und Daten über eine Anzahl von Partitionen in der Azure-Cosmos-DB-Dienst gleichmäßig zu verteilen. 
            </summary>
    <remarks>
      <para>
            Unterstützung für IPartitionResolver-basierten Klassen ist mittlerweile veraltet. Es wird empfohlen, die Verwendung von <a href="https://azure.microsoft.com/documentation/articles/documentdb-partition-data">partitionierte Sammlungen</a> für höhere Speicher und den Durchsatz.
            </para>
      <para>
            Die HashPartitionResolver-Klasse implementiert intern konsistent Hash Ring über der Hashfunktion, die im angegebenen die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> Schnittstelle. Wird standardmäßig die HashPartitionResolver bietet eine MD5-Hash-Funktion, aber dies kann durch eine andere Implementierung für hashing ausgelagert werden. Die konsistente Hash Ring erstellt 16 Replikate für jede Sammlung um eine einheitlichere Verteilung von Dokumenten über Sammlungen zu erzielen.
            </para>
      <para>
            Die Hashpartitionierung ist am besten geeigneten für die Partitionierung, wenn der Partitionsschlüssel eine hohe Kardinalität besitzt, da es die Daten gleichmäßig über Sammlungen verteilt wird. Hashpartitionierung verwendet normalerweise die Id-Eigenschaft. Eine gängige Einsatzgebiete für die Hashpartitionierung ist Daten erzeugt oder verbraucht wurde von einer großen Anzahl von unterschiedlichen Clients oder zum Speichern von Benutzerprofilen und Katalogelemente Telemetriedaten.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (Func&lt;object,string&gt; partitionKeyExtractor, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Func`2&lt;object, string&gt; partitionKeyExtractor, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.Func{System.Object,System.String},System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyExtractor As Func(Of Object, String), collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : Func&lt;obj, string&gt; * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyExtractor, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyExtractor" Type="System.Func&lt;System.Object,System.String&gt;" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyExtractor">Eine Funktion zum Extrahieren der partitionkey-Werte aus dem Dokument</param>
        <param name="collectionLinks">Die Liste der Auflistung Links, die für das hashing verwendet werden soll.</param>
        <param name="numberOfVirtualNodesPerCollection">Die Anzahl der virtuellen Knoten pro Sammlung im Ring Conisistent Hash.</param>
        <param name="hashGenerator">Die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> für die Verwendung in Hashalgorithmen konsistent. Bei null wird der standardmäßige MD5-Hash-Generator verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyExtractor" /> Wert.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HashPartitionResolver (string partitionKeyPropertyName, System.Collections.Generic.IEnumerable&lt;string&gt; collectionLinks, int numberOfVirtualNodesPerCollection = 128, Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKeyPropertyName, class System.Collections.Generic.IEnumerable`1&lt;string&gt; collectionLinks, int32 numberOfVirtualNodesPerCollection, class Microsoft.Azure.Documents.Partitioning.IHashGenerator hashGenerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.#ctor(System.String,System.Collections.Generic.IEnumerable{System.String},System.Int32,Microsoft.Azure.Documents.Partitioning.IHashGenerator)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKeyPropertyName As String, collectionLinks As IEnumerable(Of String), Optional numberOfVirtualNodesPerCollection As Integer = 128, Optional hashGenerator As IHashGenerator = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver : string * seq&lt;string&gt; * int * Microsoft.Azure.Documents.Partitioning.IHashGenerator -&gt; Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" Usage="new Microsoft.Azure.Documents.Partitioning.HashPartitionResolver (partitionKeyPropertyName, collectionLinks, numberOfVirtualNodesPerCollection, hashGenerator)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKeyPropertyName" Type="System.String" />
        <Parameter Name="collectionLinks" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="numberOfVirtualNodesPerCollection" Type="System.Int32" />
        <Parameter Name="hashGenerator" Type="Microsoft.Azure.Documents.Partitioning.IHashGenerator" />
      </Parameters>
      <Docs>
        <param name="partitionKeyPropertyName">Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</param>
        <param name="collectionLinks">Die Liste der Auflistung Links, die für das hashing verwendet werden soll.</param>
        <param name="numberOfVirtualNodesPerCollection">Die Anzahl der virtuellen Knoten pro Sammlung im Ring Conisistent Hash.</param>
        <param name="hashGenerator">Die <see cref="T:Microsoft.Azure.Documents.Partitioning.IHashGenerator" /> für die Verwendung in Hashalgorithmen konsistent. Bei null wird der standardmäßige MD5-Hash-Generator verwendet.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver" /> in der Azure-Cosmos-DB service unter Verwendung des angegebenen <paramref name="partitionKeyPropertyName" /> Wert.
            </summary>
        <remarks>
            Wird verwendet, wenn Sie basierend auf einem einzelnen Eigenschaftennamen partitionieren möchten. Verwenden Sie den Konstruktor für andere Partitionierungsschemas stattdessen mit PartitionKeyExtractor fest.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CollectionLinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;string&gt; CollectionLinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; CollectionLinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CollectionLinks As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="member this.CollectionLinks : seq&lt;string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.CollectionLinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IEnumerable Auflistung Linktypen aus, die für das hashing im Azure-Cosmos-DB-Dienst verwendet.
            </summary>
        <value>Die IEnumerable Auflistung Linktypen aus, die für das hashing verwendet werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="hashPartitionResolver.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Verwirft den Konfliktlöser im Azure-Cosmos-DB-Dienst an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~HashPartitionResolver ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="hashPartitionResolver.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Der Destruktor der Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPartitionKey">
      <MemberSignature Language="C#" Value="public virtual object GetPartitionKey (object document);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance object GetPartitionKey(object document) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.GetPartitionKey(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPartitionKey (document As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetPartitionKey : obj -&gt; obj&#xA;override this.GetPartitionKey : obj -&gt; obj" Usage="hashPartitionResolver.GetPartitionKey document" />
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
    <Member MemberName="HashGenerator">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.Partitioning.IHashGenerator HashGenerator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HashGenerator As IHashGenerator" />
      <MemberSignature Language="F#" Value="member this.HashGenerator : Microsoft.Azure.Documents.Partitioning.IHashGenerator" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.HashGenerator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.Partitioning.IHashGenerator</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die HashGenerator in konsistent Hashalgorithmen verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfVirtualNodesPerCollection">
      <MemberSignature Language="C#" Value="public int NumberOfVirtualNodesPerCollection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfVirtualNodesPerCollection As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfVirtualNodesPerCollection : int" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.NumberOfVirtualNodesPerCollection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Anzahl der virtuellen Knoten pro Sammlung im HashSet Conisistent ring im Azure-Cosmos-DB-Dienst. Diese Steuerung der Gefährdung der Schiefe von Dokumenten über Sammlungen Vs die konsistente hashing Latenz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyExtractor">
      <MemberSignature Language="C#" Value="public Func&lt;object,string&gt; PartitionKeyExtractor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;object, string&gt; PartitionKeyExtractor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyExtractor As Func(Of Object, String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyExtractor : Func&lt;obj, string&gt;" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyExtractor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Object,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Funktion zum Extrahieren von Partitionsschlüssel aus einem Objekt in der Azure-Cosmos-Datenbank ab.
            </summary>
        <value>Die Funktion, die den Partitionsschlüssel aus einem Objekt zu extrahieren.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyPropertyName">
      <MemberSignature Language="C#" Value="public string PartitionKeyPropertyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKeyPropertyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKeyPropertyName As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyPropertyName : string" Usage="Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.PartitionKeyPropertyName" />
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
            Ruft den Namen der Eigenschaft in das Dokument das hashing im Azure-Cosmos-DB-Dienst ausgeführt.
            </summary>
        <value>Der Name der Eigenschaft in das Dokument das hashing auf ausführen.</value>
        <remarks>
            HashPartitionResolver unterstützt zwei Modi - PartitionKeyPropertyName und der andere mit PartitionKeyExtractor verwenden.
            Mithilfe der Reflektion, dies der Fall ist Name für die Verwendung der c#-Eigenschaft, die JSON-Darstellung PartitionKeyPropertyName extrahiert.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveForCreate">
      <MemberSignature Language="C#" Value="public virtual string ResolveForCreate (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string ResolveForCreate(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForCreate(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForCreate (partitionKey As Object) As String" />
      <MemberSignature Language="F#" Value="abstract member ResolveForCreate : obj -&gt; string&#xA;override this.ResolveForCreate : obj -&gt; string" Usage="hashPartitionResolver.ResolveForCreate partitionKey" />
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
        <param name="partitionKey">Der Partitionsschlüssel verwendet werden, um zu bestimmen, die Zielsammlung für erstellt.</param>
        <summary>
            Erhält eine Partition drücken, gibt die Auflistung, die Self-link zum Erstellen eines Dokuments in der Azure-Cosmos-DB-Dienst.
            </summary>
        <returns>Den Link der Ziel-Auflistung, der zum Erstellen von Dokumenten verwendet werden.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn das angegebene <paramref name="partitionKey" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveForRead">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;string&gt; ResolveForRead (object partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;string&gt; ResolveForRead(object partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Partitioning.HashPartitionResolver.ResolveForRead(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ResolveForRead (partitionKey As Object) As IEnumerable(Of String)" />
      <MemberSignature Language="F#" Value="abstract member ResolveForRead : obj -&gt; seq&lt;string&gt;&#xA;override this.ResolveForRead : obj -&gt; seq&lt;string&gt;" Usage="hashPartitionResolver.ResolveForRead partitionKey" />
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
        <param name="partitionKey">Der Partitionsschlüssel verwendet, um die Zielsammlungen für das Lesen zu bestimmen. Eine Zeichenfolge muss sein.</param>
        <summary>
            Erhält eine Partition Schlüssel gibt eine Liste der Sammlung von Links mit dem Hash in der Azure-Cosmos-Datenbank gelesen.
            </summary>
        <returns>Die Liste der zielverknüpfungen-Auflistung.</returns>
        <remarks>
            Wenn PartitionKey null ist, werden alle Sammlungen zurückgegeben. Die HashPartitionResolver unterstützt nur Zeichenfolgen als PartitionKeys.
            Für andere Typen mit dem ToString()- oder JsonConvert.SerializeObject() in eine Zeichenfolge umgewandelt.
            </remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn der Partitionsschlüssel keine Zeichenfolge ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>