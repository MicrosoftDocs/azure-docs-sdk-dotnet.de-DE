<Type Name="ReplicationLink" FullName="Microsoft.Azure.Management.Sql.Models.ReplicationLink">
  <TypeSignature Language="C#" Value="public class ReplicationLink : Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReplicationLink extends Microsoft.Azure.Management.Sql.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.ReplicationLink" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicationLink&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type ReplicationLink = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.SubResource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Sql.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="52c25-101">Stellt einen datenbankreplikationslink dar.</span><span class="sxs-lookup"><span data-stu-id="52c25-101">Represents a database replication link.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLink ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ReplicationLink.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52c25-102">Initialisiert eine neue Instanz der ReplicationLink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="52c25-102">Initializes a new instance of the ReplicationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLink (string id = null, string name = null, string type = null, string location = null, Nullable&lt;bool&gt; isTerminationAllowed = null, string replicationMode = null, string partnerServer = null, string partnerDatabase = null, string partnerLocation = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; role = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; partnerRole = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;int&gt; percentComplete = null, string replicationState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, valuetype System.Nullable`1&lt;bool&gt; isTerminationAllowed, string replicationMode, string partnerServer, string partnerDatabase, string partnerLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; role, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; partnerRole, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string replicationState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.ReplicationLink.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.ReplicationRole},System.Nullable{Microsoft.Azure.Management.Sql.Models.ReplicationRole},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional isTerminationAllowed As Nullable(Of Boolean) = null, Optional replicationMode As String = null, Optional partnerServer As String = null, Optional partnerDatabase As String = null, Optional partnerLocation As String = null, Optional role As Nullable(Of ReplicationRole) = null, Optional partnerRole As Nullable(Of ReplicationRole) = null, Optional startTime As Nullable(Of DateTime) = null, Optional percentComplete As Nullable(Of Integer) = null, Optional replicationState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.ReplicationLink : string * string * string * string * Nullable&lt;bool&gt; * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Sql.Models.ReplicationLink" Usage="new Microsoft.Azure.Management.Sql.Models.ReplicationLink (id, name, type, location, isTerminationAllowed, replicationMode, partnerServer, partnerDatabase, partnerLocation, role, partnerRole, startTime, percentComplete, replicationState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isTerminationAllowed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="replicationMode" Type="System.String" />
        <Parameter Name="partnerServer" Type="System.String" />
        <Parameter Name="partnerDatabase" Type="System.String" />
        <Parameter Name="partnerLocation" Type="System.String" />
        <Parameter Name="role" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;" />
        <Parameter Name="partnerRole" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="replicationState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="52c25-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="52c25-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="52c25-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="52c25-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="52c25-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="52c25-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="52c25-106">Der Speicherort des Servers, der diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="52c25-106">Location of the server that contains this firewall rule.</span></span></param>
        <param name="isTerminationAllowed"><span data-ttu-id="52c25-107">Legacy-Wert, der angibt, ob eine Beendigung zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="52c25-107">Legacy value indicating whether termination is allowed.</span></span>  <span data-ttu-id="52c25-108">Gibt zurzeit immer "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="52c25-108">Currently always returns true.</span></span></param>
        <param name="replicationMode"><span data-ttu-id="52c25-109">Replikationsmodus von diesen Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="52c25-109">Replication mode of this replication link.</span></span></param>
        <param name="partnerServer"><span data-ttu-id="52c25-110">Der Name des Servers an, die die Partnerdatenbank hostet.</span><span class="sxs-lookup"><span data-stu-id="52c25-110">The name of the server hosting the partner database.</span></span></param>
        <param name="partnerDatabase"><span data-ttu-id="52c25-111">Der Name der Partnerdatenbank.</span><span class="sxs-lookup"><span data-stu-id="52c25-111">The name of the partner database.</span></span></param>
        <param name="partnerLocation"><span data-ttu-id="52c25-112">Die Azure-Region der Partnerdatenbank.</span><span class="sxs-lookup"><span data-stu-id="52c25-112">The Azure Region of the partner database.</span></span></param>
        <param name="role"><span data-ttu-id="52c25-113">Die Rolle der Datenbank in den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="52c25-113">The role of the database in the replication link.</span></span> <span data-ttu-id="52c25-114">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="52c25-114">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span></param>
        <param name="partnerRole"><span data-ttu-id="52c25-115">Die Rolle der Partnerdatenbank in den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="52c25-115">The role of the partner database in the replication link.</span></span> <span data-ttu-id="52c25-116">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="52c25-116">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span></param>
        <param name="startTime"><span data-ttu-id="52c25-117">Die Startzeit für den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="52c25-117">The start time for the replication link.</span></span></param>
        <param name="percentComplete"><span data-ttu-id="52c25-118">Der Prozentsatz des Seedings für den Replikationslink abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="52c25-118">The percentage of seeding complete for the replication link.</span></span></param>
        <param name="replicationState"><span data-ttu-id="52c25-119">Der Replikationsstatus für den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="52c25-119">The replication state for the replication link.</span></span> <span data-ttu-id="52c25-120">Folgende Werte sind möglich: "Ausstehend", "SEEDING", "CATCH_UP", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="52c25-120">Possible values include: 'PENDING', 'SEEDING', 'CATCH_UP', 'SUSPENDED'</span></span></param>
        <summary>
            <span data-ttu-id="52c25-121">Initialisiert eine neue Instanz der ReplicationLink-Klasse.</span><span class="sxs-lookup"><span data-stu-id="52c25-121">Initializes a new instance of the ReplicationLink class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsTerminationAllowed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsTerminationAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsTerminationAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.IsTerminationAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsTerminationAllowed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsTerminationAllowed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.IsTerminationAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isTerminationAllowed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-122">Ruft die legacy-Wert, der angibt, ob eine Beendigung zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="52c25-122">Gets legacy value indicating whether termination is allowed.</span></span>
            <span data-ttu-id="52c25-123">Gibt zurzeit immer "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="52c25-123">Currently always returns true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.Location" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.Location" />
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
            <span data-ttu-id="52c25-124">Ruft die Adresse des Servers, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="52c25-124">Gets location of the server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerDatabase">
      <MemberSignature Language="C#" Value="public string PartnerDatabase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerDatabase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerDatabase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerDatabase As String" />
      <MemberSignature Language="F#" Value="member this.PartnerDatabase : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerDatabase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerDatabase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-125">Ruft den Namen der Partnerdatenbank ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-125">Gets the name of the partner database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerLocation">
      <MemberSignature Language="C#" Value="public string PartnerLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerLocation As String" />
      <MemberSignature Language="F#" Value="member this.PartnerLocation : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-126">Ruft die Azure-Region der Partnerdatenbank ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-126">Gets the Azure Region of the partner database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerRole">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; PartnerRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; PartnerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerRole As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.PartnerRole : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-127">Ruft die Rolle Partner-Datenbank in den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-127">Gets the role of the partner database in the replication link.</span></span>
            <span data-ttu-id="52c25-128">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="52c25-128">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-129">Ruft den Namen des Servers an, die die Partnerdatenbank hostet.</span><span class="sxs-lookup"><span data-stu-id="52c25-129">Gets the name of the server hosting the partner database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.PercentComplete" />
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
            <span data-ttu-id="52c25-130">Ruft den Prozentsatz des Seedings für den Replikationslink abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="52c25-130">Gets the percentage of seeding complete for the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationMode">
      <MemberSignature Language="C#" Value="public string ReplicationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.ReplicationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationMode As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationMode : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.ReplicationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-131">Ruft die von diesen Replikationslink Replikationsmodus ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-131">Gets replication mode of this replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-132">Ruft den Replikationsstatus für den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-132">Gets the replication state for the replication link.</span></span> <span data-ttu-id="52c25-133">Folgende Werte sind möglich: "Ausstehend", "SEEDING", "CATCH_UP", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="52c25-133">Possible values include: 'PENDING', 'SEEDING', 'CATCH_UP', 'SUSPENDED'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt; Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.Role : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.role")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52c25-134">Ruft die Rolle der Datenbank in den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-134">Gets the role of the database in the replication link.</span></span> <span data-ttu-id="52c25-135">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="52c25-135">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.ReplicationLink.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.ReplicationLink.StartTime" />
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
            <span data-ttu-id="52c25-136">Ruft die Startzeit für den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="52c25-136">Gets the start time for the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>