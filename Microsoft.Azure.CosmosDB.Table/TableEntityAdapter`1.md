<Type Name="TableEntityAdapter&lt;T&gt;" FullName="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class TableEntityAdapter&lt;T&gt; : Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableEntityAdapter`1&lt;T&gt; extends Microsoft.Azure.CosmosDB.Table.TableEntity" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableEntityAdapter(Of T)&#xA;Inherits TableEntity" />
  <TypeSignature Language="F#" Value="type TableEntityAdapter&lt;'T&gt; = class&#xA;    inherit TableEntity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>Microsoft.Azure.CosmosDB.Table.TableEntity</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">Der Typ des Objekts, das Lese- und Schreibberechtigungen für Azure-Tabellenspeicher, es einer Klasse oder Struktur sein kann.</typeparam>
    <summary>
            Adapterklasse ermöglicht lesen und Schreiben von Objekten mit Azure Table Storage ohne erben von <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntity" /> Klasse oder durch Implementierung <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Schnittstelle. Die Objekte möglich POCO-Objekte, die einfache oder komplexe Objekte mit verschachtelte komplexe Eigenschaften.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; originalEntity" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
      </Parameters>
      <Docs>
        <param name="originalEntity">Das Objekt, mit Azure Table Storage geschrieben werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" />-Klasse mit dem angegebenen Objekt.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableEntityAdapter (T originalEntity, string partitionKey, string rowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T originalEntity, string partitionKey, string rowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.#ctor(`0,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (originalEntity As T, partitionKey As String, rowKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; : 'T * string * string -&gt; Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;" Usage="new Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt; (originalEntity, partitionKey, rowKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="originalEntity" Type="T" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="originalEntity">Das Objekt, mit Azure Table Storage geschrieben werden soll.</param>
        <param name="partitionKey">Eine Zeichenfolge mit dem partitionsschlüsselwert für die Entität.</param>
        <param name="rowKey">Eine Zeichenfolge mit dem zeilenschlüsselwert für die Entität.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> Klasse mit dem angegebenen Objekt, Partitionsschlüssel und Zeilenschlüssel.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalEntity">
      <MemberSignature Language="C#" Value="public T OriginalEntity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T OriginalEntity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalEntity As T" />
      <MemberSignature Language="F#" Value="member this.OriginalEntity : 'T with get, set" Usage="Microsoft.Azure.CosmosDB.Table.TableEntityAdapter&lt;'T&gt;.OriginalEntity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die ursprüngliche Entität, die gelesen und in Azure-Tabellenspeicher geschrieben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadEntity">
      <MemberSignature Language="C#" Value="public override void ReadEntity (System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ReadEntity(class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; properties, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.ReadEntity : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="tableEntityAdapter.ReadEntity (properties, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> -Objekt, das eigenschaftenzuordnungen benennt typisierten <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Werte.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Deserialisiert <see cref="T:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1" /> -Instanz mit dem angegebenen <see cref="T:System.Collections.Generic.IDictionary`2" /> Eigenschaftsnamen der ordnet die <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> zu typisierten <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Werte und speichert ihn in die <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteEntity">
      <MemberSignature Language="C#" Value="public override System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity (Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; WriteEntity(class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="override this.WriteEntity : Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="tableEntityAdapter.WriteEntity operationContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Serialisiert die <see cref="T:System.Collections.Generic.IDictionary`2" /> von Eigenschaftennamen zugeordnet <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datenwerte aus der <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> zuordnet, die zu verwendenden Objektnamen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Datentypwerte, die durch Serialisieren dieser tabellenentitätsinstanz erstellt.</returns>
        <remarks>Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> ist ein einfaches POCO-Objekt mit einfachen Eigenschaften (Grundtypen, String, Byte [],...), <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> Methode erstellt <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekten die Verwendung dieser Eigenschaften.<br />
             D. h. Eine einfache POCO Objekt A mit Eigenschaften von B und C mit dieser Struktur A -&gt;B, A -&gt;C wird konvertiert werden, um Schlüssel-Wert-Paare von {"B", EntityProperty(B)}, {"C", EntityProperty(C)}.<br />
            Wenn <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> verfügt über komplexe Eigenschaften (und möglicherweise diese Eigenschaften mit Ihren eigenen komplexe Eigenschaften) <see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.WriteEntity(Microsoft.Azure.Storage.OperationContext)" /> Methode wird vereinfachen <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> erste.<br />
            D. h. Mit einer einfachen Eigenschaft von B und komplexe Eigenschaften von C und D die haben eigene Eigenschaften E und F mit dieser Struktur ein - Objekt A&gt;B, A -&gt;C -&gt;E "und" A -&gt;d-&gt;F wird Schlüsselwert vereinfacht werden die Paare von:<br />
            {"B", EntityProperty(B)}, {"C_E", EntityProperty(E)} und {"D_F", EntityProperty(F)}.<br />
            Für jedes Schlüssel-Wert-Paar:<br />
            1. Der Schlüssel wird durch den Namen der Eigenschaften, die vom Stamm (A) zum Ende Knoteneigenschaft ("E" oder "F"), die durch "_" getrennten besucht anfügen zusammengesetzt.<br />
            2. Der Wert ist die <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" /> Objekt instanziiert, indem der Wert der Eigenschaft der End-Knoten.<br />
            Alle Schlüssel-Wert-Paare gespeichert werden im zurückgegebenen <see cref="T:System.Collections.Generic.IDictionary`2" />.<br /><see cref="M:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.ReadEntity(System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty},Microsoft.Azure.Storage.OperationContext)" />Methode recomposes der ursprünglichen Objekte (POCO oder komplexe) mithilfe der <see cref="T:System.Collections.Generic.IDictionary`2" /> von dieser Methode zurückgegebene und speichert diese im <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> Eigenschaft.<br />
            Eigenschaften, die mit markiert sind <see cref="T:Microsoft.Azure.CosmosDB.Table.IgnorePropertyAttribute" /> in die <see cref="P:Microsoft.Azure.CosmosDB.Table.TableEntityAdapter`1.OriginalEntity" /> -Objekt ignoriert und nicht von dieser Methode verarbeitet werden.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>