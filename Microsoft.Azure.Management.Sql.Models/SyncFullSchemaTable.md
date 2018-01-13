<Type Name="SyncFullSchemaTable" FullName="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable">
  <TypeSignature Language="C#" Value="public class SyncFullSchemaTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SyncFullSchemaTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable" />
  <TypeSignature Language="VB.NET" Value="Public Class SyncFullSchemaTable" />
  <TypeSignature Language="F#" Value="type SyncFullSchemaTable = class" />
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
            Eigenschaften der Tabelle in das vollständige Datenbankschema.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SyncFullSchemaTable-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SyncFullSchemaTable (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; columns = null, string errorId = null, Nullable&lt;bool&gt; hasError = null, string name = null, string quotedName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; columns, string errorId, valuetype System.Nullable`1&lt;bool&gt; hasError, string name, string quotedName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn},System.String,System.Nullable{System.Boolean},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional columns As IList(Of SyncFullSchemaTableColumn) = null, Optional errorId As String = null, Optional hasError As Nullable(Of Boolean) = null, Optional name As String = null, Optional quotedName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; * string * Nullable&lt;bool&gt; * string * string -&gt; Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable" Usage="new Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable (columns, errorId, hasError, name, quotedName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;" />
        <Parameter Name="errorId" Type="System.String" />
        <Parameter Name="hasError" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="quotedName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="columns">Liste der Spalten in der Tabelle der vollständige Datenbankschema.</param>
        <param name="errorId">Fehler-Id der Tabelle.</param>
        <param name="hasError">Wenn der Fehler in der Tabelle vorhanden ist.</param>
        <param name="name">Name der Tabelle.</param>
        <param name="quotedName">Der Name der Tabelle in Anführungszeichen.</param>
        <summary>
            Initialisiert eine neue Instanz der SyncFullSchemaTable-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Columns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; Columns { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt; Columns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Columns" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Columns As IList(Of SyncFullSchemaTableColumn)" />
      <MemberSignature Language="F#" Value="member this.Columns : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Columns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="columns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTableColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Spalten in der Tabelle der vollständige Datenbankschema ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorId">
      <MemberSignature Language="C#" Value="public string ErrorId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.ErrorId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorId As String" />
      <MemberSignature Language="F#" Value="member this.ErrorId : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.ErrorId" />
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
            Ruft die Fehler-Id der Tabelle ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.HasError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.HasError" />
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
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.Name" />
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
            Ruft den Namen der Tabelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotedName">
      <MemberSignature Language="C#" Value="public string QuotedName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotedName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.QuotedName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotedName As String" />
      <MemberSignature Language="F#" Value="member this.QuotedName : string" Usage="Microsoft.Azure.Management.Sql.Models.SyncFullSchemaTable.QuotedName" />
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
            Ruft die Namen der Tabelle in Anführungszeichen eingeschlossen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>