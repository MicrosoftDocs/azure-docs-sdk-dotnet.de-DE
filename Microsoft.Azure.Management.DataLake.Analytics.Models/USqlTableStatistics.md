<Type Name="USqlTableStatistics" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics">
  <TypeSignature Language="C#" Value="public class USqlTableStatistics : Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlTableStatistics extends Microsoft.Azure.Management.DataLake.Analytics.Models.CatalogItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlTableStatistics&#xA;Inherits CatalogItem" />
  <TypeSignature Language="F#" Value="type USqlTableStatistics = class&#xA;    inherit CatalogItem" />
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
            <span data-ttu-id="00d2b-101">Ein Data Lake Analytics U-SQL-Tabelle Statistiken Katalogelement.</span><span class="sxs-lookup"><span data-stu-id="00d2b-101">A Data Lake Analytics catalog U-SQL table statistics item.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-102">Initialisiert eine neue Instanz der USqlTableStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00d2b-102">Initializes a new instance of the USqlTableStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlTableStatistics (string computeAccountName = null, Nullable&lt;Guid&gt; version = null, string databaseName = null, string schemaName = null, string tableName = null, string name = null, string userStatName = null, string statDataPath = null, Nullable&lt;DateTimeOffset&gt; createTime = null, Nullable&lt;DateTimeOffset&gt; updateTime = null, Nullable&lt;bool&gt; isUserCreated = null, Nullable&lt;bool&gt; isAutoCreated = null, Nullable&lt;bool&gt; hasFilter = null, string filterDefinition = null, System.Collections.Generic.IList&lt;string&gt; colNames = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string computeAccountName, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; version, string databaseName, string schemaName, string tableName, string name, string userStatName, string statDataPath, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; createTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; updateTime, valuetype System.Nullable`1&lt;bool&gt; isUserCreated, valuetype System.Nullable`1&lt;bool&gt; isAutoCreated, valuetype System.Nullable`1&lt;bool&gt; hasFilter, string filterDefinition, class System.Collections.Generic.IList`1&lt;string&gt; colNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.#ctor(System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional computeAccountName As String = null, Optional version As Nullable(Of Guid) = null, Optional databaseName As String = null, Optional schemaName As String = null, Optional tableName As String = null, Optional name As String = null, Optional userStatName As String = null, Optional statDataPath As String = null, Optional createTime As Nullable(Of DateTimeOffset) = null, Optional updateTime As Nullable(Of DateTimeOffset) = null, Optional isUserCreated As Nullable(Of Boolean) = null, Optional isAutoCreated As Nullable(Of Boolean) = null, Optional hasFilter As Nullable(Of Boolean) = null, Optional filterDefinition As String = null, Optional colNames As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics : string * Nullable&lt;Guid&gt; * string * string * string * string * string * string * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics (computeAccountName, version, databaseName, schemaName, tableName, name, userStatName, statDataPath, createTime, updateTime, isUserCreated, isAutoCreated, hasFilter, filterDefinition, colNames)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="userStatName" Type="System.String" />
        <Parameter Name="statDataPath" Type="System.String" />
        <Parameter Name="createTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="updateTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="isUserCreated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isAutoCreated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hasFilter" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filterDefinition" Type="System.String" />
        <Parameter Name="colNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="computeAccountName"><span data-ttu-id="00d2b-103">der Name des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="00d2b-103">the name of the Data Lake Analytics account.</span></span></param>
        <param name="version"><span data-ttu-id="00d2b-104">die Version des Katalogelements.</span><span class="sxs-lookup"><span data-stu-id="00d2b-104">the version of the catalog item.</span></span></param>
        <param name="databaseName"><span data-ttu-id="00d2b-105">Der Name der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="00d2b-105">the name of the database.</span></span></param>
        <param name="schemaName"><span data-ttu-id="00d2b-106">der Name des Schemas, die diese Tabelle und der Datenbank zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="00d2b-106">the name of the schema associated with this table and database.</span></span></param>
        <param name="tableName"><span data-ttu-id="00d2b-107">Der Name der Tabelle.</span><span class="sxs-lookup"><span data-stu-id="00d2b-107">the name of the table.</span></span></param>
        <param name="name"><span data-ttu-id="00d2b-108">Der Name der Tabellenstatistiken.</span><span class="sxs-lookup"><span data-stu-id="00d2b-108">the name of the table statistics.</span></span></param>
        <param name="userStatName"><span data-ttu-id="00d2b-109">der Name der Benutzerstatistik.</span><span class="sxs-lookup"><span data-stu-id="00d2b-109">the name of the user statistics.</span></span></param>
        <param name="statDataPath"><span data-ttu-id="00d2b-110">der Pfad zu dem statistische Daten.</span><span class="sxs-lookup"><span data-stu-id="00d2b-110">the path to the statistics data.</span></span></param>
        <param name="createTime"><span data-ttu-id="00d2b-111">der Zeitpunkt der Erstellung der Statistik.</span><span class="sxs-lookup"><span data-stu-id="00d2b-111">the creation time of the statistics.</span></span></param>
        <param name="updateTime"><span data-ttu-id="00d2b-112">Zeitpunkt der letzten der Statistik Updates.</span><span class="sxs-lookup"><span data-stu-id="00d2b-112">the last time the statistics were updated.</span></span></param>
        <param name="isUserCreated"><span data-ttu-id="00d2b-113">der Schalter, der angibt, wenn diese Statistiken erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="00d2b-113">the switch indicating if these statistics are user created.</span></span></param>
        <param name="isAutoCreated"><span data-ttu-id="00d2b-114">der Schalter, der angibt, wenn diese Statistiken automatisch erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="00d2b-114">the switch indicating if these statistics are automatically created.</span></span></param>
        <param name="hasFilter"><span data-ttu-id="00d2b-115">der Schalter, der angibt, wenn diese Statistiken für einen Filter haben.</span><span class="sxs-lookup"><span data-stu-id="00d2b-115">the switch indicating if these statistics have a filter.</span></span></param>
        <param name="filterDefinition"><span data-ttu-id="00d2b-116">die Filterdefinition für die Statistik.</span><span class="sxs-lookup"><span data-stu-id="00d2b-116">the filter definition for the statistics.</span></span></param>
        <param name="colNames"><span data-ttu-id="00d2b-117">die Liste der Spaltennamen, die diese Statistiken zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="00d2b-117">the list of column names associated with these statistics.</span></span></param>
        <summary>
            <span data-ttu-id="00d2b-118">Initialisiert eine neue Instanz der USqlTableStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="00d2b-118">Initializes a new instance of the USqlTableStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ColNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ColNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ColNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.ColNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ColNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ColNames : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.ColNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="colNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-119">Ruft ab oder legt die Liste der Spaltennamen, die diese Statistiken zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="00d2b-119">Gets or sets the list of column names associated with these statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; CreateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; CreateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.CreateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.CreateTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.CreateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-120">Ruft ab oder legt den Zeitpunkt der Erstellung der Statistik.</span><span class="sxs-lookup"><span data-stu-id="00d2b-120">Gets or sets the creation time of the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.DatabaseName" />
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
            <span data-ttu-id="00d2b-121">Ruft ab oder legt den Namen der Datenbank fest.</span><span class="sxs-lookup"><span data-stu-id="00d2b-121">Gets or sets the name of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterDefinition">
      <MemberSignature Language="C#" Value="public string FilterDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.FilterDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterDefinition As String" />
      <MemberSignature Language="F#" Value="member this.FilterDefinition : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.FilterDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filterDefinition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-122">Ruft ab oder legt die Filterdefinition für die Statistik.</span><span class="sxs-lookup"><span data-stu-id="00d2b-122">Gets or sets the filter definition for the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasFilter">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HasFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HasFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.HasFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HasFilter As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HasFilter : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.HasFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hasFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-123">Abrufen oder festlegen den Switch, der angibt, wenn diese Statistiken für einen Filter haben.</span><span class="sxs-lookup"><span data-stu-id="00d2b-123">Gets or sets the switch indicating if these statistics have a filter.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAutoCreated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAutoCreated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAutoCreated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.IsAutoCreated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAutoCreated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAutoCreated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.IsAutoCreated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAutoCreated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-124">Ruft ab oder legt den Switch, der angibt, wenn diese Statistiken automatisch erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="00d2b-124">Gets or sets the switch indicating if these statistics are automatically created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUserCreated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUserCreated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUserCreated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.IsUserCreated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsUserCreated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUserCreated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.IsUserCreated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isUserCreated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-125">Ruft ab oder legt den Switch, der angibt, wenn diese Statistiken erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="00d2b-125">Gets or sets the switch indicating if these statistics are user created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statisticsName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-126">Ruft ab oder legt den Namen der Tabellenstatistiken.</span><span class="sxs-lookup"><span data-stu-id="00d2b-126">Gets or sets the name of the table statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchemaName">
      <MemberSignature Language="C#" Value="public string SchemaName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SchemaName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.SchemaName" />
      <MemberSignature Language="VB.NET" Value="Public Property SchemaName As String" />
      <MemberSignature Language="F#" Value="member this.SchemaName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.SchemaName" />
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
            <span data-ttu-id="00d2b-127">Ruft ab oder legt den Namen des Schemas, die diese Tabelle und der Datenbank zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="00d2b-127">Gets or sets the name of the schema associated with this table and database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatDataPath">
      <MemberSignature Language="C#" Value="public string StatDataPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatDataPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.StatDataPath" />
      <MemberSignature Language="VB.NET" Value="Public Property StatDataPath As String" />
      <MemberSignature Language="F#" Value="member this.StatDataPath : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.StatDataPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statDataPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-128">Ruft ab oder legt den Pfad fest, um die statistische Daten.</span><span class="sxs-lookup"><span data-stu-id="00d2b-128">Gets or sets the path to the statistics data.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TableName">
      <MemberSignature Language="C#" Value="public string TableName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TableName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.TableName" />
      <MemberSignature Language="VB.NET" Value="Public Property TableName As String" />
      <MemberSignature Language="F#" Value="member this.TableName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.TableName" />
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
            <span data-ttu-id="00d2b-129">Ruft ab oder legt den Namen der Tabelle fest.</span><span class="sxs-lookup"><span data-stu-id="00d2b-129">Gets or sets the name of the table.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; UpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; UpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.UpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UpdateTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.UpdateTime : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.UpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="updateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-130">Abrufen oder Festlegen der Zeitpunkt der letzten der Statistik Updates.</span><span class="sxs-lookup"><span data-stu-id="00d2b-130">Gets or sets the last time the statistics were updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserStatName">
      <MemberSignature Language="C#" Value="public string UserStatName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserStatName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.UserStatName" />
      <MemberSignature Language="VB.NET" Value="Public Property UserStatName As String" />
      <MemberSignature Language="F#" Value="member this.UserStatName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlTableStatistics.UserStatName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userStatName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="00d2b-131">Ruft ab oder legt den Namen der Benutzerstatistik fest.</span><span class="sxs-lookup"><span data-stu-id="00d2b-131">Gets or sets the name of the user statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>