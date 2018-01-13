<Type Name="TableOperation" FullName="Microsoft.Azure.CosmosDB.Table.TableOperation">
  <TypeSignature Language="C#" Value="public class TableOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableOperation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class TableOperation" />
  <TypeSignature Language="F#" Value="type TableOperation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt einen einzelnen tabellenvorgang dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Delete (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Delete(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Delete(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Delete (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Delete entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt aus der Tabelle gelöscht werden soll.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der die angegebene Entität aus einer Tabelle löscht.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Entity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.ITableEntity Entity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.ITableEntity Entity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableOperation.Entity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Entity As ITableEntity" />
      <MemberSignature Language="F#" Value="member this.Entity : Microsoft.Azure.CosmosDB.Table.ITableEntity" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Entity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.ITableEntity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Entität, die nach bearbeiteten ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Insert entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> in die Tabelle einzufügende Objekt.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Insert">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Insert (Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Insert(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity, bool echoContent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Insert(Microsoft.Azure.CosmosDB.Table.ITableEntity,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Insert (entity As ITableEntity, echoContent As Boolean) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Insert : Microsoft.Azure.CosmosDB.Table.ITableEntity * bool -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Insert (entity, echoContent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
        <Parameter Name="echoContent" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> in die Tabelle einzufügende Objekt.</param>
        <param name="echoContent">
          <c>"true"</c> , wenn die Nachrichtennutzlast in der Antwort zum Einfügevorgang zurückgegeben werden sollen. <c>"false"</c> andernfalls.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrMerge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrMerge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrMerge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrMerge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrMerge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrMerge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrMerge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt eingefügt oder zusammengeführt werden.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist. Wenn die Entität vorhanden ist, werden dessen Inhalt mit der angegebenen Entität zusammengeführt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InsertOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrReplace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation InsertOrReplace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrReplace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function InsertOrReplace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member InsertOrReplace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.InsertOrReplace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt eingefügt oder ersetzt werden.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der die angegebene Entität in eine Tabelle einfügt, wenn die Entität nicht vorhanden ist. Wenn die Entität vorhanden ist, werden dessen Inhalt durch die angegebene Entität ersetzt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Merge">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Merge (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Merge(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Merge(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Merge (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Merge : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Merge entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt zusammengeführt werden sollen.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität mit der vorhandenen Entität in einer Tabelle zusammenführt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableOperationType OperationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.CosmosDB.Table.TableOperationType OperationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.TableOperation.OperationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationType As TableOperationType" />
      <MemberSignature Language="F#" Value="member this.OperationType : Microsoft.Azure.CosmosDB.Table.TableOperationType" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.OperationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Vorgangs ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Replace (Microsoft.Azure.CosmosDB.Table.ITableEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Replace(class Microsoft.Azure.CosmosDB.Table.ITableEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Replace(Microsoft.Azure.CosmosDB.Table.ITableEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Replace (entity As ITableEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Replace : Microsoft.Azure.CosmosDB.Table.ITableEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Replace entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.ITableEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.ITableEntity" /> Objekt ersetzt werden.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle ersetzt.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve (partitionKey As String, rowkey As String, Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="partitionKey">Eine Zeichenfolge mit dem Partitionsschlüssel der Entität abgerufen werden sollen.</param>
        <param name="rowkey">Eine Zeichenfolge mit dem Zeilenschlüssel der Entität abgerufen werden sollen.</param>
        <param name="selectedColumns">Liste der Spaltennamen für die Projektion.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TElement&gt; (string partitionKey, string rowkey, System.Collections.Generic.List&lt;string&gt; selectColumns = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntity;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;(class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(string partitionKey, string rowkey, class System.Collections.Generic.List`1&lt;string&gt; selectColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve``1(System.String,System.String,System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TElement As ITableEntity) (partitionKey As String, rowkey As String, Optional selectColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity)" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, selectColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="selectColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Die Klasse der abzurufende Typ für die Entität.</typeparam>
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</param>
        <param name="rowkey">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</param>
        <param name="selectColumns">Liste der Spaltennamen für die Projektion.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retrieve&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TResult&gt; (string partitionKey, string rowkey, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, System.Collections.Generic.List&lt;string&gt; selectedColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation Retrieve&lt;TResult&gt;(string partitionKey, string rowkey, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class System.Collections.Generic.List`1&lt;string&gt; selectedColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve``1(System.String,System.String,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},System.Collections.Generic.List{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Retrieve(Of TResult) (partitionKey As String, rowkey As String, resolver As EntityResolver(Of TResult), Optional selectedColumns As List(Of String) = null) As TableOperation" />
      <MemberSignature Language="F#" Value="static member Retrieve : string * string * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * System.Collections.Generic.List&lt;string&gt; -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.Retrieve (partitionKey, rowkey, resolver, selectedColumns)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="rowkey" Type="System.String" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="selectedColumns" Type="System.Collections.Generic.List&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Rückgabetyp der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> die angegebene Entität aufgelöst wird.</typeparam>
        <param name="partitionKey">Eine Zeichenfolge, die den Partitionsschlüssel der abzurufenden Entität enthält.</param>
        <param name="rowkey">Eine Zeichenfolge, die den Zeilenschlüssel der abzurufenden Entität enthält.</param>
        <param name="resolver">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Implementierung zum projizieren der Entität als einen bestimmten Typ im Ergebnis abrufen.</param>
        <param name="selectedColumns">Liste der Spaltennamen für die Projektion.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der den Inhalt der angegebenen Entität in einer Tabelle abruft.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RotateEncryptionKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.CosmosDB.Table.TableOperation RotateEncryptionKey (Microsoft.Azure.CosmosDB.Table.KeyRotationEntity entity);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.CosmosDB.Table.TableOperation RotateEncryptionKey(class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity entity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.TableOperation.RotateEncryptionKey(Microsoft.Azure.CosmosDB.Table.KeyRotationEntity)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function RotateEncryptionKey (entity As KeyRotationEntity) As TableOperation" />
      <MemberSignature Language="F#" Value="static member RotateEncryptionKey : Microsoft.Azure.CosmosDB.Table.KeyRotationEntity -&gt; Microsoft.Azure.CosmosDB.Table.TableOperation" Usage="Microsoft.Azure.CosmosDB.Table.TableOperation.RotateEncryptionKey entity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableOperation</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entity" Type="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />
      </Parameters>
      <Docs>
        <param name="entity">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Entität über seine gedreht Schlüssel zu verfügen.  Die Ausgabe eines Aufrufs zu einem Aufruf von "ExecuteQueryForKeyRotation()" muss sein.</param>
        <summary>
            Erstellt einen neuen tabellenvorgang, der der angegebenen Entität in einer Tabelle der Inhaltsverschlüsselungsschlüssel dreht.
            </summary>
        <returns>Das <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>