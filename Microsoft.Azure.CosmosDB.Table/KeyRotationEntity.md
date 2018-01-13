<Type Name="KeyRotationEntity" FullName="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity">
  <TypeSignature Language="C#" Value="public class KeyRotationEntity" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyRotationEntity extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyRotationEntity" />
  <TypeSignature Language="F#" Value="type KeyRotationEntity = class" />
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
            Eine Entität, die für die Schlüsselrotation verwendet
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.EntityProperty this[string key] { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.EntityProperty Item(string)" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Item(System.String)" />
      <MemberSignature Language="VB.NET" Value="Default Public ReadOnly Property Item(key As String) As EntityProperty" />
      <MemberSignature Language="F#" Value="member this.Item(string) : Microsoft.Azure.CosmosDB.Table.EntityProperty" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Item" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.EntityProperty</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Eine Zeichenfolge, die mit dem Namen der Eigenschaft.</param>
        <summary>
            Ruft ab oder legt die Entitätseigenschaft erhält den Namen der Eigenschaft.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityProperty" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.CosmosDB.Table.EntityProperty&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IReadOnlyDictionary(Of String, EntityProperty)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.CosmosDB.Table.EntityProperty&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Eigenschaften in der Tabellenentität nach Eigenschaftsname indiziert ab.
            </summary>
        <value>Ein <see cref="T:System.Collections.Generic.IDictionary`2" /> Objekt, das die Eigenschaften der Entität enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RowKey">
      <MemberSignature Language="C#" Value="public string RowKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RowKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.RowKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RowKey As String" />
      <MemberSignature Language="F#" Value="member this.RowKey : string" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.RowKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset" Usage="Microsoft.Azure.CosmosDB.Table.KeyRotationEntity.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
  </Members>
</Type>