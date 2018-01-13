<Type Name="ReplicationLinkInner" FullName="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner">
  <TypeSignature Language="C#" Value="public class ReplicationLinkInner : Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ReplicationLinkInner extends Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ReplicationLinkInner&#xA;Inherits SqlSubResource" />
  <TypeSignature Language="F#" Value="type ReplicationLinkInner = class&#xA;    inherit SqlSubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Fluent.Models.SqlSubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="adeb6-101">Stellt eine Azure SQL-datenbankreplikationslink dar.</span><span class="sxs-lookup"><span data-stu-id="adeb6-101">Represents an Azure SQL database replication link.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLinkInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="adeb6-102">Initialisiert eine neue Instanz der ReplicationLinkInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="adeb6-102">Initializes a new instance of the ReplicationLinkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicationLinkInner (string name = null, string id = null, string partnerServer = null, string partnerDatabase = null, string partnerLocation = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; role = null, Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; partnerRole = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;int&gt; percentComplete = null, string replicationState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string id, string partnerServer, string partnerDatabase, string partnerLocation, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; role, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; partnerRole, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;int32&gt; percentComplete, string replicationState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole},System.Nullable{Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional id As String = null, Optional partnerServer As String = null, Optional partnerDatabase As String = null, Optional partnerLocation As String = null, Optional role As Nullable(Of ReplicationRole) = null, Optional partnerRole As Nullable(Of ReplicationRole) = null, Optional startTime As Nullable(Of DateTime) = null, Optional percentComplete As Nullable(Of Integer) = null, Optional replicationState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner : string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; * Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner" Usage="new Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner (name, id, partnerServer, partnerDatabase, partnerLocation, role, partnerRole, startTime, percentComplete, replicationState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="partnerServer" Type="System.String" />
        <Parameter Name="partnerDatabase" Type="System.String" />
        <Parameter Name="partnerLocation" Type="System.String" />
        <Parameter Name="role" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" />
        <Parameter Name="partnerRole" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="percentComplete" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="replicationState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="adeb6-103">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="adeb6-103">Resource name</span></span></param>
        <param name="id"><span data-ttu-id="adeb6-104">Die Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="adeb6-104">The resource ID.</span></span></param>
        <param name="partnerServer"><span data-ttu-id="adeb6-105">Der Name des Azure SQL Servers mit den Partner Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="adeb6-105">The name of the Azure SQL server hosting the partner Azure SQL Database.</span></span></param>
        <param name="partnerDatabase"><span data-ttu-id="adeb6-106">Der Name des Partners Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="adeb6-106">The name of the partner Azure SQL Database.</span></span></param>
        <param name="partnerLocation"><span data-ttu-id="adeb6-107">Die Azure-Region des Partners Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="adeb6-107">The Azure Region of the partner Azure SQL Database.</span></span></param>
        <param name="role"><span data-ttu-id="adeb6-108">Die Rolle der Azure SQL-Datenbank in den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="adeb6-108">The role of the Azure SQL database in the replication link.</span></span> <span data-ttu-id="adeb6-109">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="adeb6-109">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span></param>
        <param name="partnerRole"><span data-ttu-id="adeb6-110">Die Rolle des Partners Azure SQL-Datenbank in den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="adeb6-110">The role of the partner Azure SQL Database in the replication link.</span></span> <span data-ttu-id="adeb6-111">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="adeb6-111">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span></param>
        <param name="startTime"><span data-ttu-id="adeb6-112">Die Startzeit für den Replikationslink (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="adeb6-112">The start time for the replication link (ISO8601 format).</span></span></param>
        <param name="percentComplete"><span data-ttu-id="adeb6-113">Der Prozentsatz des Seedings für den Replikationslink abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="adeb6-113">The percentage of seeding complete for the replication link.</span></span></param>
        <param name="replicationState"><span data-ttu-id="adeb6-114">Der Replikationsstatus für den Replikationslink.</span><span class="sxs-lookup"><span data-stu-id="adeb6-114">The replication state for the replication link.</span></span> <span data-ttu-id="adeb6-115">Folgende Werte sind möglich: "Ausstehend", "SEEDING", "CATCH_UP", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="adeb6-115">Possible values include: 'PENDING', 'SEEDING', 'CATCH_UP', 'SUSPENDED'</span></span></param>
        <summary>
            <span data-ttu-id="adeb6-116">Initialisiert eine neue Instanz der ReplicationLinkInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="adeb6-116">Initializes a new instance of the ReplicationLinkInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerDatabase">
      <MemberSignature Language="C#" Value="public string PartnerDatabase { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerDatabase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerDatabase" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerDatabase As String" />
      <MemberSignature Language="F#" Value="member this.PartnerDatabase : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerDatabase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-117">Ruft den Namen des Partners Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-117">Gets the name of the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerLocation">
      <MemberSignature Language="C#" Value="public string PartnerLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerLocation As String" />
      <MemberSignature Language="F#" Value="member this.PartnerLocation : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-118">Ruft die Azure-Region des Partners Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-118">Gets the Azure Region of the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerRole">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; PartnerRole { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; PartnerRole" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerRole" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerRole As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.PartnerRole : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerRole" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partnerRole")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adeb6-119">Ruft die Rolle des Partners Azure SQL-Datenbank in den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-119">Gets the role of the partner Azure SQL Database in the replication link.</span></span> <span data-ttu-id="adeb6-120">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="adeb6-120">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartnerServer">
      <MemberSignature Language="C#" Value="public string PartnerServer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartnerServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerServer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartnerServer As String" />
      <MemberSignature Language="F#" Value="member this.PartnerServer : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PartnerServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-121">Ruft den Namen des Azure SQL Servers mit den Partner Azure SQL-Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-121">Gets the name of the Azure SQL server hosting the partner Azure SQL Database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PercentComplete { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PercentComplete As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-122">Ruft den Prozentsatz des Seedings für den Replikationslink abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="adeb6-122">Gets the percentage of seeding complete for the replication link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationState">
      <MemberSignature Language="C#" Value="public string ReplicationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.ReplicationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationState As String" />
      <MemberSignature Language="F#" Value="member this.ReplicationState : string" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.ReplicationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-123">Ruft den Replikationsstatus für den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-123">Gets the replication state for the replication link.</span></span> <span data-ttu-id="adeb6-124">Folgende Werte sind möglich: "Ausstehend", "SEEDING", "CATCH_UP", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="adeb6-124">Possible values include: 'PENDING', 'SEEDING', 'CATCH_UP', 'SUSPENDED'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Role">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; Role { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt; Role" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.Role" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Role As Nullable(Of ReplicationRole)" />
      <MemberSignature Language="F#" Value="member this.Role : Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.Role" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.role")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationRole&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="adeb6-125">Ruft die Rolle der Azure SQL-Datenbank in den Replikationslink ab.</span><span class="sxs-lookup"><span data-stu-id="adeb6-125">Gets the role of the Azure SQL database in the replication link.</span></span>
            <span data-ttu-id="adeb6-126">Folgende Werte sind möglich: 'Primary', 'Sekundären', "NonReadableSecondary", "Source", "Kopieren"</span><span class="sxs-lookup"><span data-stu-id="adeb6-126">Possible values include: 'Primary', 'Secondary', 'NonReadableSecondary', 'Source', 'Copy'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.Models.ReplicationLinkInner.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="adeb6-127">Ruft die Startzeit für den Replikationslink (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="adeb6-127">Gets the start time for the replication link (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>