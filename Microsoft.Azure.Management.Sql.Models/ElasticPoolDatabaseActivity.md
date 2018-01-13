<Type Name="ElasticPoolDatabaseActivity" FullName="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity">
  <TypeSignature Language="C#" Value="public class ElasticPoolDatabaseActivity : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ElasticPoolDatabaseActivity extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity" />
  <TypeSignature Language="VB.NET" Value="Public Class ElasticPoolDatabaseActivity&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ElasticPoolDatabaseActivity = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="f0a69-101">Stellt die Aktivität in einem elastischen Pool dar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-101">Represents the activity on an elastic pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDatabaseActivity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-102">Initialisiert eine neue Instanz der ElasticPoolDatabaseActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f0a69-102">Initializes a new instance of the ElasticPoolDatabaseActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ElasticPoolDatabaseActivity (string id = null, string name = null, string type = null, string location = null, string databaseName = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; errorCode = null, string errorMessage = null, Nullable&lt;int&gt; errorSeverity = null, string operation = null, Guid operationId = null, Nullable&lt;int&gt; percentComplete = null, string requestedElasticPoolName = null, string currentElasticPoolName = null, string currentServiceObjective = null, string requestedServiceObjective = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, string databaseName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorMessage, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, string operation, valuetype System.Guid operationId, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string requestedElasticPoolName, string currentElasticPoolName, string currentServiceObjective, string requestedServiceObjective, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.String,System.Guid,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional databaseName As String = null, Optional endTime As Nullable(Of DateTime) = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorMessage As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional operation As String = null, Optional operationId As Guid = null, Optional percentComplete As Nullable(Of Integer) = null, Optional requestedElasticPoolName As String = null, Optional currentElasticPoolName As String = null, Optional currentServiceObjective As String = null, Optional requestedServiceObjective As String = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * string * Guid * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity" Usage="new Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity (id, name, type, location, databaseName, endTime, errorCode, errorMessage, errorSeverity, operation, operationId, percentComplete, requestedElasticPoolName, currentElasticPoolName, currentServiceObjective, requestedServiceObjective, serverName, startTime, state)" />
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
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorMessage" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestedElasticPoolName" Type="System.String" />
        <Parameter Name="currentElasticPoolName" Type="System.String" />
        <Parameter Name="currentServiceObjective" Type="System.String" />
        <Parameter Name="requestedServiceObjective" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f0a69-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="f0a69-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="f0a69-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f0a69-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="f0a69-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="f0a69-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="f0a69-106">Der geografische Standort, in dem die Ressource aktiv ist</span><span class="sxs-lookup"><span data-stu-id="f0a69-106">The geo-location where the resource lives</span></span></param>
        <param name="databaseName"><span data-ttu-id="f0a69-107">Der Datenbankname.</span><span class="sxs-lookup"><span data-stu-id="f0a69-107">The database name.</span></span></param>
        <param name="endTime"><span data-ttu-id="f0a69-108">Die Zeit, die der Vorgang abgeschlossen, (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="f0a69-108">The time the operation finished (ISO8601 format).</span></span></param>
        <param name="errorCode"><span data-ttu-id="f0a69-109">Der Fehlercode, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-109">The error code if available.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="f0a69-110">Die Fehlermeldung, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-110">The error message if available.</span></span></param>
        <param name="errorSeverity"><span data-ttu-id="f0a69-111">Schweregrad des Fehlers falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-111">The error severity if available.</span></span></param>
        <param name="operation"><span data-ttu-id="f0a69-112">Der Name des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f0a69-112">The operation name.</span></span></param>
        <param name="operationId"><span data-ttu-id="f0a69-113">Die eindeutige Vorgangs-ID.</span><span class="sxs-lookup"><span data-stu-id="f0a69-113">The unique operation ID.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="f0a69-114">Der Prozentsatz abgeschlossen, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-114">The percentage complete if available.</span></span></param>
        <param name="requestedElasticPoolName"><span data-ttu-id="f0a69-115">Der Name für den elastischen Pool, dem die Datenbank in verschoben wird, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-115">The name for the elastic pool the database is moving into if available.</span></span></param>
        <param name="currentElasticPoolName"><span data-ttu-id="f0a69-116">Der Name des aktuellen elastischen Pools If wird die Datenbank verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-116">The name of the current elastic pool the database is in if available.</span></span></param>
        <param name="currentServiceObjective"><span data-ttu-id="f0a69-117">Der Name des aktuellen dienstziels, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-117">The name of the current service objective if available.</span></span></param>
        <param name="requestedServiceObjective"><span data-ttu-id="f0a69-118">Der Name des angeforderten dienstziels, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-118">The name of the requested service objective if available.</span></span></param>
        <param name="serverName"><span data-ttu-id="f0a69-119">Der Name des Servers der elastische Pool wird.</span><span class="sxs-lookup"><span data-stu-id="f0a69-119">The name of the server the elastic pool is in.</span></span></param>
        <param name="startTime"><span data-ttu-id="f0a69-120">Beim Start des Vorgangs (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="f0a69-120">The time the operation started (ISO8601 format).</span></span></param>
        <param name="state"><span data-ttu-id="f0a69-121">Der aktuelle Status des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f0a69-121">The current state of the operation.</span></span></param>
        <summary>
            <span data-ttu-id="f0a69-122">Initialisiert eine neue Instanz der ElasticPoolDatabaseActivity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f0a69-122">Initializes a new instance of the ElasticPoolDatabaseActivity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentElasticPoolName">
      <MemberSignature Language="C#" Value="public string CurrentElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentElasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-123">Ruft den Namen des aktuellen elastischen Pools, der die Datenbank befindet sich im If verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-123">Gets the name of the current elastic pool the database is in if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjective">
      <MemberSignature Language="C#" Value="public string CurrentServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.CurrentServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-124">Ruft den Namen des aktuellen dienstziels ab, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-124">Gets the name of the current service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.DatabaseName" />
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
            <span data-ttu-id="f0a69-125">Ruft den Datenbanknamen ab.</span><span class="sxs-lookup"><span data-stu-id="f0a69-125">Gets the database name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-126">Ruft den Zeitpunkt der Vorgang abgeschlossen, (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="f0a69-126">Gets the time the operation finished (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-127">Ruft den Fehlercode ab, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-127">Gets the error code if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public string ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As String" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-128">Ruft die Fehlermeldung ab, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-128">Gets the error message if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ErrorSeverity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorSeverity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-129">Ruft den Schweregrad des Fehlers ab, sofern verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-129">Gets the error severity if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Location" />
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
            <span data-ttu-id="f0a69-130">Ruft ab oder legt den geografischen Standort aktiv ist, in dem die Ressource</span><span class="sxs-lookup"><span data-stu-id="f0a69-130">Gets or sets the geo-location where the resource lives</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-131">Ruft den Vorgangsnamen.</span><span class="sxs-lookup"><span data-stu-id="f0a69-131">Gets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-132">Ruft die eindeutige Vorgangs-ID ab.</span><span class="sxs-lookup"><span data-stu-id="f0a69-132">Gets the unique operation ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-133">Ruft den Prozentsatz abgeschlossen, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-133">Gets the percentage complete if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedElasticPoolName">
      <MemberSignature Language="C#" Value="public string RequestedElasticPoolName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedElasticPoolName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedElasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-134">Ruft den Namen für den elastischen Pool, dem die Datenbank gegebenenfalls auf verschoben werden.</span><span class="sxs-lookup"><span data-stu-id="f0a69-134">Gets the name for the elastic pool the database is moving into if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjective">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestedServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.RequestedServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-135">Ruft den Namen des Ziels angeforderten Dienst ab, falls verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f0a69-135">Gets the name of the requested service objective if available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.ServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-136">Ruft den Namen des Servers ein, die in der elastische Pool ist.</span><span class="sxs-lookup"><span data-stu-id="f0a69-136">Gets the name of the server the elastic pool is in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-137">Ruft den Zeitpunkt der Vorgang (ISO8601-Format) gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="f0a69-137">Gets the time the operation started (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.ElasticPoolDatabaseActivity.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f0a69-138">Ruft den aktuellen Status des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="f0a69-138">Gets the current state of the operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>