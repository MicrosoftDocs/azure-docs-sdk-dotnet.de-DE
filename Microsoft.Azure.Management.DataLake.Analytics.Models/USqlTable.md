<Type Name="USqlTable" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable">
  <TypeSignature Language="C#" Value="public class USqlTable : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTable extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTable&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTable = class&#xA;    inherit CatalogItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein Data Lake Analytics U-SQL-Tabelle Katalogelement.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der USqlTable-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTable (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; columnList = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; indexList = null, System.Collections.Generic.IList&lt;string&gt; partitionKeyList = null, Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable externalTable = null, Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo distributionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; columnList, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; indexList, class System.Collections.Generic.IList`1&lt;string&gt; partitionKeyList, class Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable externalTable, class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo distributionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable,Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable : string * Nullable&lt;Guid&gt; * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable * Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable (computeAccountName, version, databaseName, schemaName, name, columnList, indexList, partitionKeyList, externalTable, distributionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="computeAccountName" Type="System.String" />
        <Parameter Name="version" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="schemaName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="columnList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt;" />
        <Parameter Name="indexList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt;" />
        <Parameter Name="partitionKeyList" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="externalTable" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable" />
        <Parameter Name="distributionInfo" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" />
      </Parameters>
      <Docs>
        <param name="computeAccountName">der Name des Data Lake Analytics-Kontos.</param>
        <param name="version">die Version des Katalogelements.</param>
        <param name="databaseName">Der Name der Datenbank.</param>
        <param name="schemaName">der Name des Schemas, die diese Tabelle und der Datenbank zugeordnet.</param>
        <param name="name">Der Name der Tabelle.</param>
        <param name="columnList">die Liste der Spalten in dieser Tabelle</param>
        <param name="indexList">die Liste der Indizes in dieser Tabelle</param>
        <param name="partitionKeyList">die Liste der Partitionsschlüssel in der Tabelle</param>
        <param name="externalTable">die externe Tabelle, die der Tabelle zugeordnet.</param>
        <param name="distributionInfo">die Verteilungen Informationen der Tabelle</param>
        <summary>
            Initialisiert eine neue Instanz der USqlTable-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColumnList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; ColumnList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; ColumnList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.ColumnList" />
      <MemberSignature Language="VB.NET" Value="Public Property ColumnList As IList(Of USqlTableColumn)" />
      <MemberSignature Language="F#" Value="member this.ColumnList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.ColumnList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columnList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Spalten in dieser Tabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Datenbank fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DistributionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo DistributionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo DistributionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.DistributionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property DistributionInfo As USqlDistributionInfo" />
      <MemberSignature Language="F#" Value="member this.DistributionInfo : Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.DistributionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distributionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verteilungen Informationen der Tabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExternalTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable ExternalTable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable ExternalTable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.ExternalTable" />
      <MemberSignature Language="VB.NET" Value="Public Property ExternalTable As ExternalTable" />
      <MemberSignature Language="F#" Value="member this.ExternalTable : Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.ExternalTable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="externalTable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.ExternalTable</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die externe Tabelle, die der Tabelle zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; IndexList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; IndexList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.IndexList" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexList As IList(Of USqlIndex)" />
      <MemberSignature Language="F#" Value="member this.IndexList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.IndexList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlIndex&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Indizes in dieser Tabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tableName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Tabelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionKeyList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PartitionKeyList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PartitionKeyList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.PartitionKeyList" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKeyList As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PartitionKeyList : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.PartitionKeyList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionKeyList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Partitionsschlüssel in der Tabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTable.SchemaName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schemaName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Schemas, die diese Tabelle und der Datenbank zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>