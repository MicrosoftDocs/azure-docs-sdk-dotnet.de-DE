<Type Name="DatabaseOperation" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseOperation">
  <TypeSignature Language="C#" Value="public class DatabaseOperation : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseOperation extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseOperation" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseOperation&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type DatabaseOperation = class&#xA;    inherit ProxyResource" />
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
            <span data-ttu-id="2b977-101">Ein Datenbankvorgang.</span><span class="sxs-lookup"><span data-stu-id="2b977-101">A database operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseOperation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2b977-102">Initialisiert eine neue Instanz der Klasse DatabaseOperation.</span><span class="sxs-lookup"><span data-stu-id="2b977-102">Initializes a new instance of the DatabaseOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseOperation (string id = null, string name = null, string type = null, string databaseName = null, string operation = null, string operationFriendlyName = null, Nullable&lt;int&gt; percentComplete = null, string serverName = null, Nullable&lt;DateTime&gt; startTime = null, string state = null, Nullable&lt;int&gt; errorCode = null, string errorDescription = null, Nullable&lt;int&gt; errorSeverity = null, Nullable&lt;bool&gt; isUserError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string databaseName, string operation, string operationFriendlyName, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string serverName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, string state, valuetype System.Nullable`1&lt;int32&gt; errorCode, string errorDescription, valuetype System.Nullable`1&lt;int32&gt; errorSeverity, valuetype System.Nullable`1&lt;bool&gt; isUserError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.Nullable{System.DateTime},System.String,System.Nullable{System.Int32},System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional databaseName As String = null, Optional operation As String = null, Optional operationFriendlyName As String = null, Optional percentComplete As Nullable(Of Integer) = null, Optional serverName As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional state As String = null, Optional errorCode As Nullable(Of Integer) = null, Optional errorDescription As String = null, Optional errorSeverity As Nullable(Of Integer) = null, Optional isUserError As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseOperation : string * string * string * string * string * string * Nullable&lt;int&gt; * string * Nullable&lt;DateTime&gt; * string * Nullable&lt;int&gt; * string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseOperation" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseOperation (id, name, type, databaseName, operation, operationFriendlyName, percentComplete, serverName, startTime, state, errorCode, errorDescription, errorSeverity, isUserError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="operationFriendlyName" Type="System.String" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="errorCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="errorDescription" Type="System.String" />
        <Parameter Name="errorSeverity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isUserError" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="2b977-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="2b977-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="2b977-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="2b977-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="2b977-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="2b977-105">Resource type.</span></span></param>
        <param name="databaseName"><span data-ttu-id="2b977-106">Der Name der Datenbank wird auf der Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b977-106">The name of the database the operation is being performed on.</span></span></param>
        <param name="operation"><span data-ttu-id="2b977-107">Der Name des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2b977-107">The name of operation.</span></span></param>
        <param name="operationFriendlyName"><span data-ttu-id="2b977-108">Der angezeigte Name des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2b977-108">The friendly name of operation.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="2b977-109">Der Prozentsatz der der Vorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="2b977-109">The percentage of the operation completed.</span></span></param>
        <param name="serverName"><span data-ttu-id="2b977-110">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="2b977-110">The name of the server.</span></span></param>
        <param name="startTime"><span data-ttu-id="2b977-111">Die Startzeit für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2b977-111">The operation start time.</span></span></param>
        <param name="state"><span data-ttu-id="2b977-112">Der Status des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2b977-112">The operation state.</span></span> <span data-ttu-id="2b977-113">Folgende Werte sind möglich: "Ausstehend", "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "CancelInProgress", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="2b977-113">Possible values include: 'Pending', 'InProgress', 'Succeeded', 'Failed', 'CancelInProgress', 'Cancelled'</span></span></param>
        <param name="errorCode"><span data-ttu-id="2b977-114">Der Fehlercode für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2b977-114">The operation error code.</span></span></param>
        <param name="errorDescription"><span data-ttu-id="2b977-115">Die fehlerbeschreibung für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="2b977-115">The operation error description.</span></span></param>
        <param name="errorSeverity"><span data-ttu-id="2b977-116">Der Vorgang Fehlerschweregrad.</span><span class="sxs-lookup"><span data-stu-id="2b977-116">The operation error severity.</span></span></param>
        <param name="isUserError"><span data-ttu-id="2b977-117">Der Fehler ist, und zwar unabhängig davon, ob ein Benutzerfehler.</span><span class="sxs-lookup"><span data-stu-id="2b977-117">Whether or not the error is a user error.</span></span></param>
        <summary>
            <span data-ttu-id="2b977-118">Initialisiert eine neue Instanz der Klasse DatabaseOperation.</span><span class="sxs-lookup"><span data-stu-id="2b977-118">Initializes a new instance of the DatabaseOperation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseName">
      <MemberSignature Language="C#" Value="public string DatabaseName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.DatabaseName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseName As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.DatabaseName" />
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
            <span data-ttu-id="2b977-119">Ruft den Namen der Datenbank, die, der für der Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="2b977-119">Gets the name of the database the operation is being performed on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorCode" />
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
            <span data-ttu-id="2b977-120">Ruft den Fehlercode für den Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-120">Gets the operation error code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorDescription">
      <MemberSignature Language="C#" Value="public string ErrorDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ErrorDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorDescription As String" />
      <MemberSignature Language="F#" Value="member this.ErrorDescription : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errorDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b977-121">Ruft die Beschreibung des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-121">Gets the operation error description.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorSeverity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ErrorSeverity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ErrorSeverity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorSeverity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorSeverity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ErrorSeverity : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ErrorSeverity" />
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
            <span data-ttu-id="2b977-122">Ruft den Schweregrad des Fehlers Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-122">Gets the operation error severity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsUserError">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsUserError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsUserError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.IsUserError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsUserError As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsUserError : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.IsUserError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isUserError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b977-123">Ruft ab, und zwar unabhängig davon, ob der Fehler ein Fehler ist.</span><span class="sxs-lookup"><span data-stu-id="2b977-123">Gets whether or not the error is a user error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.Operation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.Operation" />
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
            <span data-ttu-id="2b977-124">Ruft den Namen des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-124">Gets the name of operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationFriendlyName">
      <MemberSignature Language="C#" Value="public string OperationFriendlyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationFriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.OperationFriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationFriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.OperationFriendlyName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.OperationFriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationFriendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2b977-125">Ruft den Anzeigenamen des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-125">Gets the friendly name of operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.PercentComplete" />
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
            <span data-ttu-id="2b977-126">Ruft den Prozentsatz der der Vorgang abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="2b977-126">Gets the percentage of the operation completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerName">
      <MemberSignature Language="C#" Value="public string ServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServerName As String" />
      <MemberSignature Language="F#" Value="member this.ServerName : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.ServerName" />
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
            <span data-ttu-id="2b977-127">Ruft den Namen des Servers ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-127">Gets the name of the server.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.StartTime" />
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
            <span data-ttu-id="2b977-128">Ruft die Startzeit des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-128">Gets the operation start time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseOperation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseOperation.State" />
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
            <span data-ttu-id="2b977-129">Ruft den Status des Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="2b977-129">Gets the operation state.</span></span> <span data-ttu-id="2b977-130">Folgende Werte sind möglich: "Ausstehend", "InProgress", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "CancelInProgress", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="2b977-130">Possible values include: 'Pending', 'InProgress', 'Succeeded', 'Failed', 'CancelInProgress', 'Cancelled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>