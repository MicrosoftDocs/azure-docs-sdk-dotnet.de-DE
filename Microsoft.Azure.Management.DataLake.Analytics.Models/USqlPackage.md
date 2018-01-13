<Type Name="USqlPackage" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage">
  <TypeSignature Language="C#" Value="public class USqlPackage : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlPackage extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlPackage&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlPackage = class&#xA;    inherit CatalogItem" />
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
            Ein Data Lake Analytics U-SQL-Paket Katalogelement.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlPackage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der USqlPackage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlPackage (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string name = null, string definition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string name, string definition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional name As String = null, Optional definition As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage : string * Nullable&lt;Guid&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage (computeAccountName, version, databaseName, schemaName, name, definition)" />
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
        <param name="databaseName">Der Name der Datenbank, die das Paket enthält.</param>
        <param name="schemaName">der Name der Datenbank und dem Paket zugeordnete Schema.</param>
        <param name="name">Der Name des Pakets.</param>
        <param name="definition">die Definition des Pakets.</param>
        <summary>
            Initialisiert eine neue Instanz der USqlPackage-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.DatabaseName" />
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
            Ruft ab oder legt den Namen der Datenbank, die das Paket enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Definition">
      <MemberSignature Language="C#" Value="public string Definition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Definition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Definition" />
      <MemberSignature Language="VB.NET" Value="Public Property Definition As String" />
      <MemberSignature Language="F#" Value="member this.Definition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Definition" />
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
            Ruft ab oder legt die Definition des Pakets fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="packageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Pakets.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlPackage.SchemaName" />
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
            Ruft ab oder legt den Namen der Datenbank und dem Paket zugeordnete Schema.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>