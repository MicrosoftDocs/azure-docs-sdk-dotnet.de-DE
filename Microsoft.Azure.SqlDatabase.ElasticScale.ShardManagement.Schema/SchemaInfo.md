<Type Name="SchemaInfo" FullName="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo">
  <TypeSignature Language="C#" Value="public class SchemaInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit SchemaInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class SchemaInfo" />
  <TypeSignature Language="F#" Value="type SchemaInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
    <AssemblyVersion>1.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="Schema", Namespace="")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Collections.Generic.HashSet`1&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Collections.Generic.HashSet`1&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt Informationen zur Kennzeichnung der Liste der Sharding-Tabellen und die Liste der Verweistabellen, die ein shardingschema zugeordnet. Verweistabellen werden über Shards hinweg repliziert.
            Diese Klasse ist threadsicher.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SchemaInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo referenceTableInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo referenceTableInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.Add(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo)" />
      <MemberSignature Language="F#" Value="member this.Add : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo -&gt; unit" Usage="schemaInfo.Add referenceTableInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="ReferenceTableInfo class already validates its members.", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="referenceTableInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" />
      </Parameters>
      <Docs>
        <param name="referenceTableInfo">Tabelleninformationen Verweis.</param>
        <summary>
            Fügt Informationen zu einer Verweistabelle.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo shardedTableInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo shardedTableInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.Add(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo)" />
      <MemberSignature Language="F#" Value="member this.Add : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo -&gt; unit" Usage="schemaInfo.Add shardedTableInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="ShardedTableInfo class already validates its members.", MessageId="0")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardedTableInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" />
      </Parameters>
      <Docs>
        <param name="shardedTableInfo">Informationen zu shardtabelle.</param>
        <summary>
            Fügt Informationen zu einer Tabelle mit Shards.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReferenceTables">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt; ReferenceTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt; ReferenceTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.ReferenceTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReferenceTables As ReadOnlyCollection(Of ReferenceTableInfo)" />
      <MemberSignature Language="F#" Value="member this.ReferenceTables : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.ReferenceTables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Schreibgeschützte Liste von Informationen zu allen Verweistabellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo referenceTableInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Remove(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo referenceTableInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.Remove(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo)" />
      <MemberSignature Language="F#" Value="member this.Remove : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo -&gt; bool" Usage="schemaInfo.Remove referenceTableInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="referenceTableInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ReferenceTableInfo" />
      </Parameters>
      <Docs>
        <param name="referenceTableInfo">Tabelleninformationen Verweis.</param>
        <summary>
            Entfernt die Informationen zu einer Verweistabelle.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public bool Remove (Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo shardedTableInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Remove(class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo shardedTableInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.Remove(Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo)" />
      <MemberSignature Language="F#" Value="member this.Remove : Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo -&gt; bool" Usage="schemaInfo.Remove shardedTableInfo" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shardedTableInfo" Type="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo" />
      </Parameters>
      <Docs>
        <param name="shardedTableInfo">Informationen zu shardtabelle.</param>
        <summary>
            Entfernt die Informationen zu einer Tabelle mit Shards.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardedTables">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt; ShardedTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt; ShardedTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.ShardedTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ShardedTables As ReadOnlyCollection(Of ShardedTableInfo)" />
      <MemberSignature Language="F#" Value="member this.ShardedTables : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;" Usage="Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.SchemaInfo.ShardedTables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.SqlDatabase.ElasticScale.Client</AssemblyName>
        <AssemblyVersion>1.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.Azure.SqlDatabase.ElasticScale.ShardManagement.Schema.ShardedTableInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Schreibgeschützte Liste von Informationen über alle Sharding-Tabellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>