<Type Name="TableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.TableEntity">
  <TypeSignature Language="C#" Value="public class TableEntity : Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi TableEntity extends System.Object implements class Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type TableEntity = class&#xA;    interface ITableEntity" />
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
      <InterfaceName>Microsoft.WindowsAzure.Storage.Table.ITableEntity</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt den Basisobjekttyp für eine Tabellenentität im Tabellendienst dar.
            </summary>
    <remarks>
      <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />Stellt eine basisimplementierung für die <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Schnittstelle, bietet <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden, die standardmäßig serialisieren und Deserialisieren alle Eigenschaften über Reflektion ermöglicht. Eine tabellenentitätsklasse kann diese Klasse erweitert und überschreiben die <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" /> und <see cref="M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" /> Methoden bieten angepasste oder leistungsstärkere Serialisierungslogik.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.TableEntity : string * string -&gt; Microsoft.WindowsAzure.Storage.Table.TableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.TableEntity (partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der enthält die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> initialisiert werden.</param>
        <param name="rowKey">Eine Zeichenfolge, die den Zeilenschlüssel der enthält die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> initialisiert werden.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ des recomposed-Objekts. Dies kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie sein.</typeparam>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine benutzerdefinierte Entitätsinstanz, die neu aufgebaut wird unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datentypwerte.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertBack&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static TResult ConvertBack&lt;TResult&gt; (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!TResult ConvertBack&lt;TResult&gt;(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack``1(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ConvertBack : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; 'Result" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ConvertBack (properties, entityPropertyConverterOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ des recomposed-Objekts. Dies kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie sein.</typeparam>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</param>
        <param name="entityPropertyConverterOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine benutzerdefinierte Entitätsinstanz, die neu aufgebaut wird unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datentypwerte.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableCompiledSerializers">
      <MemberSignature Language="C#" Value="public static bool DisableCompiledSerializers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisableCompiledSerializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.DisableCompiledSerializers" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisableCompiledSerializers As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableCompiledSerializers : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.DisableCompiledSerializers" />
      <MemberType>Property</MemberType>
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
            Deaktiviert die Fähigkeit zum dynamischen Generieren von lesen und Schreiben von Lambdas zur Laufzeit. Diese Einstellung auf "false" festgelegt wird, allen Typinstanzen, die von TableEntity abgeleitet werden gemeinsam genutzte statischen Cache gelöscht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisablePropertyResolverCache">
      <MemberSignature Language="C#" Value="public static bool DisablePropertyResolverCache { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property bool DisablePropertyResolverCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberSignature Language="VB.NET" Value="Public Shared Property DisablePropertyResolverCache As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisablePropertyResolverCache : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.DisablePropertyResolverCache" />
      <MemberType>Property</MemberType>
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
            Ruft ab oder legt den Status der Eigenschaftencache Konfliktlöser für die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" />. 
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Konfliktlöser Eigenschaftencache zwischenspeichert bekannte Entitätstypen und ihre jeweiligen Konfliktlöser Wörterbücher, wenn Entitäten deserialisiert werden, und die Nutzlast enthält keine JSON-Metadaten. In den meisten Szenarien wird das Deaktivieren der Konfliktlöser Eigenschaftencache aufgrund seiner Effekte auf die Leistung nicht empfohlen. 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ETag" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ETag</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt das ETag der Entität. Legen Sie diesen Wert auf "*" zum Überschreiben einer Entität als Teil eines Updatevorgangs zu erzwingen.
            </summary>
        <value>Eine Zeichenfolge mit dem ETag-Wert für die Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object entity, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten (entity, operationContext)" />
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
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">Das zu serialisierende Entitätsobjekt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Fasst die Entität und erstellt eine <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</returns>
        <remarks>Der Entitätstyp kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie.
            Generische ConvertBack-Methode kann die ursprüngliche Entität mithilfe den Rückgabewert dieser Methode neu aufzubauen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flatten">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten (object entity, Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Flatten(object entity, class Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions entityPropertyConverterOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten(System.Object,Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member Flatten : obj * Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Flatten (entity, entityPropertyConverterOptions, operationContext)" />
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
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="entityPropertyConverterOptions" Type="Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">Das zu serialisierende Entitätsobjekt.</param>
        <param name="entityPropertyConverterOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityPropertyConverterOptions" /> -Objekt, das Optionen für die Konvertierung der Entität-Eigenschaft angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Fasst die Entität und erstellt eine <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</returns>
        <remarks>Der Entitätstyp kann ein einfaches Objekt mit einer flachen Struktur oder ein komplexes Objekt komplexe Eigenschaften, die mit mehreren Ebenen der Objekthierarchie.
            Generische ConvertBack-Methode kann die ursprüngliche Entität mithilfe den Rückgabewert dieser Methode neu aufzubauen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.PartitionKey</InterfaceMember>
      </Implements>
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
            Ruft ab, oder legt ihn fest Partitionsschlüssel der Entität.
            </summary>
        <value>Eine Zeichenfolge, die den Partitionsschlüssel der Entität enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public virtual void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="tableEntity.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
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
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> -Objekt, das eigenschaftenzuordnungen benennt typisierten <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Werte.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Deserialisiert die Entität mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> ordnet Eigenschaftsnamen typisierten <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Werte. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadUserObject">
      <MemberSignature Language="C#" Value="public static void ReadUserObject (object entity, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ReadUserObject(object entity, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadUserObject(System.Object,System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member ReadUserObject : obj * System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.ReadUserObject (entity, properties, operationContext)" />
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
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">Die benutzerdefinierte Entitätsinstanz, die deserialisiert wird.</param>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datenwerte deserialisiert und gespeichert, die in dieser tabellenentitätsinstanz.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Deserialisiert eine benutzerdefinierte Entitätsinstanz unter Verwendung des angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen für <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datentypwerte. 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.RowKey" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.RowKey</InterfaceMember>
      </Implements>
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
            Ruft ab, oder legt ihn fest Zeilenschlüssel der Entität.
            </summary>
        <value>Eine Zeichenfolge, die den Zeilenschlüssel der Entität enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.WindowsAzure.Storage.Table.ITableEntity.Timestamp</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt den Zeitstempel der Entität.
            </summary>
        <value>Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel der Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="tableEntity.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.WindowsAzure.Storage.Table.ITableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)</InterfaceMember>
      </Implements>
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
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> -Datenwerten aus dieser <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableEntity" /> Instanz.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteUserObject">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteUserObject (object entity, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteUserObject(object entity, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteUserObject(System.Object,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="static member WriteUserObject : obj * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="Microsoft.WindowsAzure.Storage.Table.TableEntity.WriteUserObject (entity, operationContext)" />
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
        <Parameter Name="entity" Type="System.Object" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="entity">Das zu serialisierende Entitätsobjekt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Erstellen einer <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> von <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> Objekte für alle Eigenschaften des angegebenen Entitätsobjekts.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>