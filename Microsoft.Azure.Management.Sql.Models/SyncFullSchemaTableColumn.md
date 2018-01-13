<Type Name="SyncFullSchemaTableColumn" FullName="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn">
  <TypeSignature Language="C#" Value="public class SyncFullSchemaTableColumn" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncFullSchemaTableColumn extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncFullSchemaTableColumn" />
  <TypeSignature Language="F#" Value="type SyncFullSchemaTableColumn = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften der Spalte in der Tabelle der vollständige Datenbankschema.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTableColumn ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SyncFullSchemaTableColumn-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTableColumn (string dataSize = null, string dataType = null, string errorId = null, Nullable&lt;bool&gt; hasError = null, Nullable&lt;bool&gt; isPrimaryKey = null, string name = null, string quotedName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string dataSize, string dataType, string errorId, valuetype System.Nullable`1&lt;bool&gt; hasError, valuetype System.Nullable`1&lt;bool&gt; isPrimaryKey, string name, string quotedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.#ctor(System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dataSize As String = null, Optional dataType As String = null, Optional errorId As String = null, Optional hasError As Nullable(Of Boolean) = null, Optional isPrimaryKey As Nullable(Of Boolean) = null, Optional name As String = null, Optional quotedName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn : string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn" Usage="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn (dataSize, dataType, errorId, hasError, isPrimaryKey, name, quotedName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dataSize" Type="System.String" />
        <Parameter Name="dataType" Type="System.String" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="hasError" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isPrimaryKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="quotedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dataSize">Die Größe der Daten der Spalte.</param>
        <param name="dataType">Datentyp der Spalte.</param>
        <param name="errorId">Fehler-Id der Spalte.</param>
        <param name="hasError">Wenn der Fehler in der Tabelle vorhanden ist.</param>
        <param name="isPrimaryKey">Wenn der Primärschlüssel der Tabelle ist.</param>
        <param name="name">Name der Spalte.</param>
        <param name="quotedName">Der Name der Spalte in Anführungszeichen.</param>
        <summary>
            Initialisiert eine neue Instanz der SyncFullSchemaTableColumn-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSize">
      <MemberSignature Language="C#" Value="public string DataSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSize As String" />
      <MemberSignature Language="F#" Value="member this.DataSize : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe der Daten der Spalte ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataType">
      <MemberSignature Language="C#" Value="public string DataType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataType As String" />
      <MemberSignature Language="F#" Value="member this.DataType : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.DataType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Datentyp der Spalte ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.ErrorId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Fehler-Id der Spalte ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.HasError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.HasError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hasError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, wenn der Fehler in der Tabelle vorhanden ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPrimaryKey">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsPrimaryKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsPrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.IsPrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrimaryKey As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsPrimaryKey : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.IsPrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isPrimaryKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, ob sie den Primärschlüssel der Tabelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Spalte.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn.QuotedName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotedName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Namen der Spalte in Anführungszeichen eingeschlossen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>