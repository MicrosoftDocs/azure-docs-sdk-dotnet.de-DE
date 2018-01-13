<Type Name="USqlTablePartition" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition">
  <TypeSignature Language="C#" Value="public class USqlTablePartition : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTablePartition extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTablePartition&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTablePartition = class&#xA;    inherit CatalogItem" />
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
            Ein Data Lake Analytics U-SQL-Tabelle Partition Katalogelement.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTablePartition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der USqlTablePartition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTablePartition (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName parentName = null, Nullable&lt;int&gt; indexId = null, System.Collections.Generic.IList&lt;string&gt; label = null, Nullable&lt;DateTimeOffset&gt; createDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, class Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName parentName, valuetype System.Nullable`1&lt;int32&gt; indexId, class System.Collections.Generic.IList`1&lt;string&gt; label, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; createDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional parentName As DdlName = null, Optional indexId As Nullable(Of Integer) = null, Optional label As IList(Of String) = null, Optional createDate As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition : string * Nullable&lt;Guid&gt; * string * string * string * Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition (computeAccountName, version, databaseName, schemaName, name, parentName, indexId, label, createDate)" />
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
        <Parameter Name="parentName" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName" />
        <Parameter Name="indexId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="label" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="createDate" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName">der Name des Data Lake Analytics-Kontos.</param>
        <param name="version">die Version des Katalogelements.</param>
        <param name="databaseName">Der Name der Datenbank.</param>
        <param name="schemaName">der Name des Schemas, die diese Tabellenpartition und die Datenbank zugeordnet.</param>
        <param name="name">Der Name der Tabellenpartition.</param>
        <param name="parentName">Die Partition übergeordneten Ddl-Objekt.</param>
        <param name="indexId">Die Index-ID für diese Partition.</param>
        <param name="label">die Liste der Bezeichnungen, die diese Partition zugeordnet.</param>
        <param name="createDate">der Zeitpunkt der Erstellung der partition</param>
        <summary>
            Initialisiert eine neue Instanz der USqlTablePartition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; CreateDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; CreateDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.CreateDate" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateDate As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.CreateDate : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.CreateDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt der Erstellung der partition
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.DatabaseName" />
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
    <Member MemberName="IndexId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IndexId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IndexId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.IndexId" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IndexId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.IndexId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="indexId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Index-ID für diese Partition.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Label : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="label")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Bezeichnungen, die diese Partition zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Tabellenpartition fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParentName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName ParentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName ParentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.ParentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ParentName As DdlName" />
      <MemberSignature Language="F#" Value="member this.ParentName : Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.ParentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.DdlName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Ddl-Objekt, der die Partition übergeordneten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTablePartition.SchemaName" />
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
            Ruft ab oder legt den Namen des Schemas, die diese Tabellenpartition und die Datenbank zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>