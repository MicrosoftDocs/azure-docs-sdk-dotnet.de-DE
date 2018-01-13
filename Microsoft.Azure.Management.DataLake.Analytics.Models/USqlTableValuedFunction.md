<Type Name="USqlTableValuedFunction" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction">
  <TypeSignature Language="C#" Value="public class USqlTableValuedFunction : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTableValuedFunction extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTableValuedFunction&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTableValuedFunction = class&#xA;    inherit CatalogItem" />
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
            Ein Data Lake Analytics U-SQL-Tabelle Inlinefunktion Katalogelement.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableValuedFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der USqlTableValuedFunction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableValuedFunction (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, string definition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, string definition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional definition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction : string * Nullable&lt;Guid&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction (computeAccountName, version, databaseName, schemaName, name, definition)" />
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
        <Parameter Name="definition" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="computeAccountName">der Name des Data Lake Analytics-Kontos.</param>
        <param name="version">die Version des Katalogelements.</param>
        <param name="databaseName">Der Name der Datenbank.</param>
        <param name="schemaName">der Name des Schemas, die dieser Datenbank zugeordnet.</param>
        <param name="name">der Name der Tabelle die Tabellenwertfunktion an.</param>
        <param name="definition">die Definition der Tabellenwertfunktion.</param>
        <summary>
            Initialisiert eine neue Instanz der USqlTableValuedFunction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.DatabaseName" />
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
    <Member MemberName="Definition">
      <MemberSignature Language="C#" Value="public string Definition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Definition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Definition" />
      <MemberSignature Language="VB.NET" Value="Public Property Definition As String" />
      <MemberSignature Language="F#" Value="member this.Definition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Definition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="definition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Definition der Tabellenwertfunktion.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tvfName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Tabellenwert-Funktion.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableValuedFunction.SchemaName" />
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
            Ruft ab oder legt den Namen des Schemas, die dieser Datenbank zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>