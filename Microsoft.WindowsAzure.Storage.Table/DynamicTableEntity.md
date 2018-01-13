<Type Name="DynamicTableEntity" FullName="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity">
  <TypeSignature Language="C#" Value="public sealed class DynamicTableEntity : Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DynamicTableEntity extends System.Object implements class Microsoft.WindowsAzure.Storage.Table.ITableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DynamicTableEntity&#xA;Implements ITableEntity" />
  <TypeSignature Language="F#" Value="type DynamicTableEntity = class&#xA;    interface ITableEntity" />
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
            Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" /> Typ, der Aufrufern den direkten Zugriff auf die eigenschaftszuordnung der Entität ermöglicht. Diese Klasse erübrigt die Verwendung von Reflektion für die Serialisierung und Deserialisierung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor" />
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
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity : string * string -&gt; Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity (partitionKey, rowKey)" />
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
        <param name="partitionKey">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</param>
        <param name="rowKey">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Klasse mit dem angegebenen Partitionsschlüssel und Zeilenschlüssel.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DynamicTableEntity (string partitionKey, string rowKey, string etag, System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string partitionKey, string rowKey, string etag, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (partitionKey As String, rowKey As String, etag As String, properties As IDictionary(Of String, EntityProperty))" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity : string * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" Usage="new Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity (partitionKey, rowKey, etag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</param>
        <param name="rowKey">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</param>
        <param name="etag">Eine Zeichenfolge, die das ETag für die Entität enthält.</param>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt mit Eigenschaften der Entität nach Eigenschaftsnamen indiziert.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Klasse mit dem Partitionsschlüssel, Zeilenschlüssel, ETag (wenn verfügbar, erforderlich) und Eigenschaften der Entität.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ETag" />
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
            Ruft ab oder legt das aktuelle ETag der Entität.
            </summary>
        <value>Eine Zeichenfolge, die das ETag für die Entität enthält.</value>
        <remarks>Legen Sie diesen Wert auf "*" auf eine Entität als Teil eines Updatevorgangs Blind zu überschreiben.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Item">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.EntityProperty this[string key] { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.WindowsAzure.Storage.Table.EntityProperty with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eine Zeichenfolge, die mit dem Namen der Eigenschaft.</param>
        <summary>
            Ruft ab oder legt die Entitätseigenschaft erhält den Namen der Eigenschaft.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.PartitionKey" />
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
        <value>Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften in der Tabellenentität nach Eigenschaftsname indiziert.
            </summary>
        <value>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften der Entität enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; properties, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.WindowsAzure.Storage.Table.EntityProperty},Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="dynamicTableEntity.ReadEntity (properties, operationContext)" />
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
        <param name="properties">Eine Auflistung mit den <see cref="T:System.Collections.Generic.IDictionary`2" /> der zeichenfolgeneigenschaftsnamen zu Werten vom Typ zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> zum Speichern von in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Deserialisiert diese <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> -Instanz mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen zu Werten vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" />.
            </summary>
        <remarks>Im Eigenschaftenwörterbuch an die API übergeben werden intern als Verweis, keine Kopie gespeichert.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.RowKey" />
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
        <value>Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.Timestamp" />
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
        <value>Ein <see cref="T:System.DateTimeOffset" /> mit dem Zeitstempel für die Entität.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity (Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt; WriteEntity(class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity.WriteEntity(Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;&#xA;override this.WriteEntity : Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.WindowsAzure.Storage.Table.EntityProperty&gt;" Usage="dynamicTableEntity.WriteEntity operationContext" />
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
            Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftsnamen zu Werten vom Typ zugeordnet <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> aus diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt mit der Zuordnung der zeichenfolgeneigenschaftsnamen zu Werten vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.Table.EntityProperty" /> gespeichert, die in diesem <see cref="T:Microsoft.WindowsAzure.Storage.Table.DynamicTableEntity" /> Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>