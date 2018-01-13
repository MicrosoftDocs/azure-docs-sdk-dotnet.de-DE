<Type Name="ITableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.ITableEntity">
  <TypeSignature Language="C#" Value="public interface ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITableEntity" />
  <TypeSignature Language="F#" Value="type ITableEntity = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d8179-101">Eine Schnittstelle, die für tabellenentitätstypen erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="d8179-101">An interface required for table entity types.</span></span> <span data-ttu-id="d8179-102">Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Schnittstelle deklariert Getter- und Setter-Methoden für die erforderlichen Entitätseigenschaften und <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden für die Serialisierung und Deserialisierung aller Entitätseigenschaften, die ein Eigenschaftenwörterbuch verwenden.</span><span class="sxs-lookup"><span data-stu-id="d8179-102">The <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> interface declares getter and setter methods for the mandatory entity properties, and <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> and <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> methods for serialization and de-serialization of all entity properties using a property dictionary.</span></span> <span data-ttu-id="d8179-103">Erstellen von Klassen implementieren <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Eigenschaftspeicher, abrufen, Serialisierung und Deserialisierung anpassen und zusätzlichen benutzerdefinierte Logik für eine Tabellenentität bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="d8179-103">Create classes implementing <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> to customize property storage, retrieval, serialization and de-serialization, and to provide additional custom logic for a table entity.</span></span>
            </summary>
    <remarks>
      <para><span data-ttu-id="d8179-104">Die speicherclientbibliothek enthält zwei Implementierungen von <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> , die für einfache Eigenschaftenzugriff und Serialisierung bereitstellen:</span><span class="sxs-lookup"><span data-stu-id="d8179-104">The storage client library includes two implementations of <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> that provide for simple property access and serialization:</span></span></para>
      <para>
        <span data-ttu-id="d8179-105"><see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />implementiert <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> und bietet ein einfaches Eigenschaftenwörterbuch zum Speichern und Abrufen von Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="d8179-105"><see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> implements <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> and provides a simple property dictionary to store and retrieve properties.</span></span> <span data-ttu-id="d8179-106">Verwenden einer <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> für den einfachen Zugriff auf Entitätseigenschaften, wenn nur eine Teilmenge der Eigenschaften (z. B. durch eine select-Klausel in einer Abfrage) zurückgegeben werden, oder für Szenarien, in denen die Abfrage mehrere Entitätstypen mit verschiedenen Eigenschaften zurückgeben kann.</span><span class="sxs-lookup"><span data-stu-id="d8179-106">Use a <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> for simple access to entity properties when only a subset of properties are returned (for example, by a select clause in a query), or for scenarios where your query can return multiple entity types with different properties.</span></span> <span data-ttu-id="d8179-107">Sie können auch dieses Typs verwenden, um massentabellenaktualisierungen von heterogenen Entitäten ohne Verlust von Eigenschaftsinformationen auszuführen.</span><span class="sxs-lookup"><span data-stu-id="d8179-107">You can also use this type to perform bulk table updates of heterogeneous entities without losing property information.</span></span></para>
      <para>
        <span data-ttu-id="d8179-108"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />ist eine Implementierung von <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> , verwendet reflektionsbasierte Serialisierung und Deserialisierung Verhalten in seiner <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden.</span><span class="sxs-lookup"><span data-stu-id="d8179-108"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> is an implementation of <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> that uses reflection-based serialization and de-serialization behavior in its <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> and <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> methods.</span></span> 
            <span data-ttu-id="d8179-109"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-abgeleitete Klassen mit Methoden, die Dateinamenskonvention für Typen- und Namenskonvention werden automatisch serialisiert und deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="d8179-109"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-derived classes with methods that follow a convention for types and naming are serialized and deserialized automatically.</span></span> <span data-ttu-id="d8179-110"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-abgeleitete Klassen müssen auch eine öffentliche Get-able- und Set-able-Eigenschaft eines Typs, die vom Microsoft Azure-Tabellendienst unterstützt angeben.</span><span class="sxs-lookup"><span data-stu-id="d8179-110"><see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-derived classes must also provide a get-able and set-able public property of a type that is supported by the Microsoft Azure Table service.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8179-111">Ruft ab oder legt das aktuelle ETag der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-111">Gets or sets the entity's current ETag.</span></span>  <span data-ttu-id="d8179-112">Legen Sie diesen Wert auf "\*" um eine Entität als Teil eines Updatevorgangs Blind zu überschreiben.</span><span class="sxs-lookup"><span data-stu-id="d8179-112">Set this value to '\*' in order to blindly overwrite an entity as part of an update operation.</span></span>
            </summary>
        <value><span data-ttu-id="d8179-113">Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-113">The entity's timestamp.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8179-114">Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-114">Gets or sets the entity's partition key.</span></span>
            </summary>
        <value><span data-ttu-id="d8179-115">Der Partitionsschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-115">The entity's partition key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="iTableEntity.ReadEntity (properties, operationContext)" />
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
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties"><span data-ttu-id="d8179-116">Das Wörterbuch mit zeichenfolgeneigenschaftsnamen für <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</span><span class="sxs-lookup"><span data-stu-id="d8179-116">The dictionary of string property names to <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> data values to deserialize and store in this table entity instance.</span></span></param>
        <param name="operationContext"><span data-ttu-id="d8179-117">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d8179-117">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8179-118">Füllt die Eigenschaften der Entität aus der <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte in der <paramref name="properties" /> Wörterbuch.</span><span class="sxs-lookup"><span data-stu-id="d8179-118">Populates the entity's properties from the <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> data values in the <paramref name="properties" /> dictionary.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8179-119">Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-119">Gets or sets the entity's row key.</span></span>
            </summary>
        <value><span data-ttu-id="d8179-120">Zeilenschlüssel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-120">The entity's row key.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d8179-121">Ruft ab oder legt den Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-121">Gets or sets the entity's timestamp.</span></span>
            </summary>
        <value><span data-ttu-id="d8179-122">Zeitstempel der Entität.</span><span class="sxs-lookup"><span data-stu-id="d8179-122">The entity's timestamp.</span></span> <span data-ttu-id="d8179-123">Die Eigenschaft wird vom Microsoft Azure-Tabellendienst aufgefüllt.</span><span class="sxs-lookup"><span data-stu-id="d8179-123">The property is populated by the Microsoft Azure Table Service.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="iTableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext"><span data-ttu-id="d8179-124">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="d8179-124">An <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> object that represents the context for the current operation.</span></span></param>
        <summary>
            <span data-ttu-id="d8179-125">Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte aus der Entitätsinstanz.</span><span class="sxs-lookup"><span data-stu-id="d8179-125">Serializes the <see cref="T:System.Collections.Generic.IDictionary`2" /> of property names mapped to <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> data values from the entity instance.</span></span>
            </summary>
        <returns><span data-ttu-id="d8179-126">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt von Eigenschaftennamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</span><span class="sxs-lookup"><span data-stu-id="d8179-126">An <see cref="T:System.Collections.Generic.IDictionary`2" /> object of property names to <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> data typed values created by serializing this table entity instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>