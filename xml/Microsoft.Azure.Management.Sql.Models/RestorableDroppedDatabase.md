<Type Name="RestorableDroppedDatabase" FullName="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase">
  <TypeSignature Language="C#" Value="public class RestorableDroppedDatabase : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RestorableDroppedDatabase extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase" />
  <TypeSignature Language="VB.NET" Value="Public Class RestorableDroppedDatabase&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type RestorableDroppedDatabase = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="86213-101">Wiederherstellbare gelöschte Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-101">A restorable dropped database</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestorableDroppedDatabase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="86213-102">Initialisiert eine neue Instanz der RestorableDroppedDatabase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="86213-102">Initializes a new instance of the RestorableDroppedDatabase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestorableDroppedDatabase (string id = null, string name = null, string type = null, string location = null, string databaseName = null, string edition = null, string maxSizeBytes = null, string serviceLevelObjective = null, string elasticPoolName = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;DateTime&gt; deletionDate = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, string databaseName, string edition, string maxSizeBytes, string serviceLevelObjective, string elasticPoolName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional databaseName As String = null, Optional edition As String = null, Optional maxSizeBytes As String = null, Optional serviceLevelObjective As String = null, Optional elasticPoolName As String = null, Optional creationDate As Nullable(Of DateTime) = null, Optional deletionDate As Nullable(Of DateTime) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase : string * string * string * string * string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase" Usage="new Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase (id, name, type, location, databaseName, edition, maxSizeBytes, serviceLevelObjective, elasticPoolName, creationDate, deletionDate, earliestRestoreDate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="deletionDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="86213-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="86213-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="86213-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="86213-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="86213-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="86213-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="86213-106">Der geografische Standort, in dem die Ressource aktiv ist</span><span class="sxs-lookup"><span data-stu-id="86213-106">The geo-location where the resource lives</span></span></param>
        <param name="databaseName"><span data-ttu-id="86213-107">der Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-107">The name of the database</span></span></param>
        <param name="edition"><span data-ttu-id="86213-108">Die Edition der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-108">The edition of the database</span></span></param>
        <param name="maxSizeBytes"><span data-ttu-id="86213-109">Die maximale Größe in Byte der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-109">The max size in bytes of the database</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="86213-110">Die SLO-Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-110">The service level objective name of the database</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="86213-111">Der elastische Poolname der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-111">The elastic pool name of the database</span></span></param>
        <param name="creationDate"><span data-ttu-id="86213-112">Das Erstellungsdatum der Datenbank (ISO8601-Format)</span><span class="sxs-lookup"><span data-stu-id="86213-112">The creation date of the database (ISO8601 format)</span></span></param>
        <param name="deletionDate"><span data-ttu-id="86213-113">Das Löschdatum der Datenbank (ISO8601-Format)</span><span class="sxs-lookup"><span data-stu-id="86213-113">The deletion date of the database (ISO8601 format)</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="86213-114">Das früheste Wiederherstellungsdatum der Datenbank (ISO8601-Format)</span><span class="sxs-lookup"><span data-stu-id="86213-114">The earliest restore date of the database (ISO8601 format)</span></span></param>
        <summary>
            <span data-ttu-id="86213-115">Initialisiert eine neue Instanz der RestorableDroppedDatabase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="86213-115">Initializes a new instance of the RestorableDroppedDatabase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-116">Ruft das Erstellungsdatum der Datenbank (ISO8601-Format)</span><span class="sxs-lookup"><span data-stu-id="86213-116">Gets the creation date of the database (ISO8601 format)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.DatabaseName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-117">Ruft den Namen der Datenbank ab</span><span class="sxs-lookup"><span data-stu-id="86213-117">Gets the name of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletionDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.DeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletionDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.DeletionDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deletionDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-118">Ruft das Löschdatum der Datenbank (ISO8601-Format)</span><span class="sxs-lookup"><span data-stu-id="86213-118">Gets the deletion date of the database (ISO8601 format)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.earliestRestoreDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-119">Ruft wiederherstellen das früheste Datum der Datenbank (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="86213-119">Gets the earliest restore date of the database (ISO8601 format)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.Edition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-120">Ruft die Edition der Datenbank ab</span><span class="sxs-lookup"><span data-stu-id="86213-120">Gets the edition of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-121">Ruft den elastischen Pool-Namen der Datenbank ab</span><span class="sxs-lookup"><span data-stu-id="86213-121">Gets the elastic pool name of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-122">Ruft den geografischen Standort aktiv ist, in dem die Ressource</span><span class="sxs-lookup"><span data-stu-id="86213-122">Gets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-123">Ruft die maximale Größe in Byte der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-123">Gets the max size in bytes of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.RestorableDroppedDatabase.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="86213-124">Ruft die SLO-Name der Datenbank</span><span class="sxs-lookup"><span data-stu-id="86213-124">Gets the service level objective name of the database</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>