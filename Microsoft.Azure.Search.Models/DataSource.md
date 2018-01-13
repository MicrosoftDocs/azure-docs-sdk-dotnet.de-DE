<Type Name="DataSource" FullName="Microsoft.Azure.Search.Models.DataSource">
  <TypeSignature Language="C#" Value="public class DataSource : Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataSource extends System.Object implements class Microsoft.Azure.Search.Models.IResourceWithETag" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class DataSource&#xA;Implements IResourceWithETag" />
  <TypeSignature Language="F#" Value="type DataSource = class&#xA;    interface IResourceWithETag" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Search.Models.IResourceWithETag</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Stellt eine Datenquellendefinition in Azure Search dar, mit dem ein Indexer konfiguriert werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataSource (string name, Microsoft.Azure.Search.Models.DataSourceType type, Microsoft.Azure.Search.Models.DataSourceCredentials credentials, Microsoft.Azure.Search.Models.DataContainer container, string description = null, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy = null, string eTag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.DataSourceType type, class Microsoft.Azure.Search.Models.DataSourceCredentials credentials, class Microsoft.Azure.Search.Models.DataContainer container, string description, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy dataChangeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy dataDeletionDetectionPolicy, string eTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.#ctor(System.String,Microsoft.Azure.Search.Models.DataSourceType,Microsoft.Azure.Search.Models.DataSourceCredentials,Microsoft.Azure.Search.Models.DataContainer,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DataSource : string * Microsoft.Azure.Search.Models.DataSourceType * Microsoft.Azure.Search.Models.DataSourceCredentials * Microsoft.Azure.Search.Models.DataContainer * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="new Microsoft.Azure.Search.Models.DataSource (name, type, credentials, container, description, dataChangeDetectionPolicy, dataDeletionDetectionPolicy, eTag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Search.Models.DataSourceType" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Search.Models.DataSourceCredentials" />
        <Parameter Name="container" Type="Microsoft.Azure.Search.Models.DataContainer" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="dataChangeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="dataDeletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="eTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="type">Der Typ der Datenquelle.</param>
        <param name="credentials">Anmeldeinformationen für die Datenquelle.</param>
        <param name="container">Der Datencontainer für die Datenquelle.</param>
        <param name="description">Die Beschreibung der Datenquelle.</param>
        <param name="dataChangeDetectionPolicy">Die Datenänderung Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="dataDeletionDetectionPolicy">Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="eTag">Das ETag der Datenquelle.</param>
        <summary>
            Initialisiert eine neue Instanz der DataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBlobStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureBlobStorage (string name, string storageConnectionString, string containerName, string pathPrefix = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureBlobStorage(string name, string storageConnectionString, string containerName, string pathPrefix, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureBlobStorage (name As String, storageConnectionString As String, containerName As String, Optional pathPrefix As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureBlobStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureBlobStorage (name, storageConnectionString, containerName, pathPrefix, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="pathPrefix" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="storageConnectionString">Die Verbindungszeichenfolge für das Azure-Speicherkonto an. Er muss folgendem Format entsprechen: "DefaultEndpointsProtocol = Https; AccountName = [Ihr Speicherkonto]; AccountKey = [Ihr kontoschlüssel]; " Beachten Sie, dass HTTPS erforderlich ist.</param>
        <param name="containerName">Der Name des Containers aus dem Blobs gelesen werden soll.</param>
        <param name="pathPrefix">Optional. Wenn angegeben, umfasst die Datenquelle nur Blobs mit Namen mit diesem Präfix beginnen. Dies ist hilfreich, wenn Blobs z. B. in "virtuelle Ordner" organisiert sind.</param>
        <param name="deletionDetectionPolicy">Optional. Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit einem Azure-Blob-Container.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="changeDetectionPolicy">Die Erkennungsrichtlinie für für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle mit änderungserkennung aktiviert die Verbindung mit einer Azure SQL-Datenbank.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="deletionDetectionPolicy">Optional. Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit einer Azure SQL-Datenbank.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureSql">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureSql (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureSql(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureSql(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureSql (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureSql : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureSql (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die Azure SQL-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="changeDetectionPolicy">Die Erkennungsrichtlinie für für die Datenquelle. Beachten Sie, nur das Kontingent Erkennung zu ändern ist für SQL Azure zulässig, wenn löschen Erkennung aktiviert ist.</param>
        <param name="deletionDetectionPolicy">Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit einer Azure SQL-Datenbank mit änderungserkennung und Erkennung des Löschvorgänge aktiviert.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureTableStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource AzureTableStorage (string name, string storageConnectionString, string tableName, string query = null, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource AzureTableStorage(string name, string storageConnectionString, string tableName, string query, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.AzureTableStorage(System.String,System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function AzureTableStorage (name As String, storageConnectionString As String, tableName As String, Optional query As String = null, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member AzureTableStorage : string * string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.AzureTableStorage (name, storageConnectionString, tableName, query, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="storageConnectionString" Type="System.String" />
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="storageConnectionString">Die Verbindungszeichenfolge für das Azure-Speicherkonto an. Er muss folgendem Format entsprechen: "DefaultEndpointsProtocol = Https; AccountName = [Ihr Speicherkonto]; AccountKey = [Ihr kontoschlüssel]; " Beachten Sie, dass HTTPS erforderlich ist.</param>
        <param name="tableName">Der Name der Tabelle, aus der gelesenen Zeilen.</param>
        <param name="query">Optional. Eine Abfrage, die beim Lesen von Zeilen in der Tabelle angewendet wird.</param>
        <param name="deletionDetectionPolicy">Optional. Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit einer Azure-Tabelle.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataContainer Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataContainer Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As DataContainer" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Search.Models.DataContainer with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataContainer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Datencontainer für die Datenquelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceCredentials Credentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public Property Credentials As DataSourceCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Search.Models.DataSourceCredentials with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="credentials")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anmeldeinformationen für die Datenquelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataChangeDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy DataChangeDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataChangeDetectionPolicy As DataChangeDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataChangeDetectionPolicy : Microsoft.Azure.Search.Models.DataChangeDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataChangeDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataChangeDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataChangeDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Erkennungsrichtlinie für für die Datenquelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDeletionDetectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy DataDeletionDetectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDeletionDetectionPolicy As DataDeletionDetectionPolicy" />
      <MemberSignature Language="F#" Value="member this.DataDeletionDetectionPolicy : Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.DataDeletionDetectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dataDeletionDetectionPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Erkennungsrichtlinie für die Datenquelle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Beschreibung der Datenquelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentDb">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource DocumentDb (string name, string documentDbConnectionString, string collectionName, string query = null, bool useChangeDetection = true, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource DocumentDb(string name, string documentDbConnectionString, string collectionName, string query, bool useChangeDetection, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.DocumentDb(System.String,System.String,System.String,System.String,System.Boolean,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DocumentDb (name As String, documentDbConnectionString As String, collectionName As String, Optional query As String = null, Optional useChangeDetection As Boolean = true, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member DocumentDb : string * string * string * string * bool * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.DocumentDb (name, documentDbConnectionString, collectionName, query, useChangeDetection, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="documentDbConnectionString" Type="System.String" />
        <Parameter Name="collectionName" Type="System.String" />
        <Parameter Name="query" Type="System.String" />
        <Parameter Name="useChangeDetection" Type="System.Boolean" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="documentDbConnectionString">Die Verbindungszeichenfolge für die DocumentDb-Datenbank. Er muss folgendem Format entsprechen: "AccountName | AccountEndpoint = [Ihr Kontoname oder der Endpunkt]; AccountKey = [Ihr kontoschlüssel]; Database = [Ihre Datenbankname] "</param>
        <param name="collectionName">Der Name der Auflistung, um Dokumente zu lesen.</param>
        <param name="query">Optional. Eine Abfrage, die auf die Auflistung angewendet wird, wenn Dokumente gelesen.</param>
        <param name="useChangeDetection">Optional. Gibt an, ob änderungserkennung verwendet beim indizieren. Der Standardwert ist true.</param>
        <param name="deletionDetectionPolicy">Optional. Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit DocumentDb-Datenbank.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="@odata.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag der Datenquelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Namen der Datenquelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataChangeDetectionPolicy changeDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataChangeDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As DataChangeDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataChangeDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataChangeDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="changeDetectionPolicy">Die Erkennungsrichtlinie für für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle mit änderungserkennung aktiviert die Verbindung mit einer VM-gehostete SQL Server-Datenbank.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy = null, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, Optional deletionDetectionPolicy As DataDeletionDetectionPolicy = null, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="deletionDetectionPolicy">Optional. Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung mit einer VM-gehostete SQL Server-Datenbank.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerOnAzureVM">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM (string name, string sqlConnectionString, string tableOrViewName, Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource SqlServerOnAzureVM(string name, string sqlConnectionString, string tableOrViewName, class Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy changeDetectionPolicy, class Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy deletionDetectionPolicy, string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM(System.String,System.String,System.String,Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy,Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlServerOnAzureVM (name As String, sqlConnectionString As String, tableOrViewName As String, changeDetectionPolicy As HighWaterMarkChangeDetectionPolicy, deletionDetectionPolicy As DataDeletionDetectionPolicy, Optional description As String = null) As DataSource" />
      <MemberSignature Language="F#" Value="static member SqlServerOnAzureVM : string * string * string * Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy * Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy * string -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.Models.DataSource.SqlServerOnAzureVM (name, sqlConnectionString, tableOrViewName, changeDetectionPolicy, deletionDetectionPolicy, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="sqlConnectionString" Type="System.String" />
        <Parameter Name="tableOrViewName" Type="System.String" />
        <Parameter Name="changeDetectionPolicy" Type="Microsoft.Azure.Search.Models.HighWaterMarkChangeDetectionPolicy" />
        <Parameter Name="deletionDetectionPolicy" Type="Microsoft.Azure.Search.Models.DataDeletionDetectionPolicy" />
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Datenquelle.</param>
        <param name="sqlConnectionString">Die Verbindungszeichenfolge für die SQL Server-Datenbank.</param>
        <param name="tableOrViewName">Der Name der Tabelle oder Sicht aus dem Zeilen gelesen werden soll.</param>
        <param name="changeDetectionPolicy">Die Erkennungsrichtlinie für für die Datenquelle. Beachten Sie, nur das Kontingent Erkennung zu ändern ist für SQL Server zulässig, wenn löschen Erkennung aktiviert ist.</param>
        <param name="deletionDetectionPolicy">Die Erkennungsrichtlinie für die Datenquelle.</param>
        <param name="description">Optional. Beschreibung der Datenquelle.</param>
        <summary>
            Erstellt eine neue Datenquelle für die Verbindung zu einer VM-gehostete SQL Server-Datenbank mit änderungserkennung und Löschung konflikterkennung zu aktivieren.
            </summary>
        <returns>Eine neue Datenquelleninstanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DataSourceType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DataSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As DataSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Search.Models.DataSourceType with get, set" Usage="Microsoft.Azure.Search.Models.DataSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Datenquelle fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DataSource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="dataSource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>