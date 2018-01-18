<Type Name="SelfHostedIntegrationRuntimeStatus" FullName="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus">
  <TypeSignature Language="C#" Value="public class SelfHostedIntegrationRuntimeStatus : Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SelfHostedIntegrationRuntimeStatus extends Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus" />
  <TypeSignature Language="VB.NET" Value="Public Class SelfHostedIntegrationRuntimeStatus&#xA;Inherits IntegrationRuntimeStatus" />
  <TypeSignature Language="F#" Value="type SelfHostedIntegrationRuntimeStatus = class&#xA;    inherit IntegrationRuntimeStatus" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.IntegrationRuntimeStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("SelfHosted")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="99242-101">Common Language Runtime Integrationsstatus gehostet.</span><span class="sxs-lookup"><span data-stu-id="99242-101">Self-hosted integration runtime status.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SelfHostedIntegrationRuntimeStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99242-102">Initialisiert eine neue Instanz der SelfHostedIntegrationRuntimeStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99242-102">Initializes a new instance of the SelfHostedIntegrationRuntimeStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SelfHostedIntegrationRuntimeStatus (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string state = null, Nullable&lt;DateTime&gt; createTime = null, string taskQueueId = null, string internalChannelEncryption = null, string version = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; nodes = null, Nullable&lt;DateTime&gt; scheduledUpdateDate = null, string updateDelayOffset = null, string localTimeZoneOffset = null, System.Collections.Generic.IDictionary&lt;string,string&gt; capabilities = null, System.Collections.Generic.IList&lt;string&gt; serviceUrls = null, string autoUpdate = null, string versionStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createTime, string taskQueueId, string internalChannelEncryption, string version, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; nodes, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; scheduledUpdateDate, string updateDelayOffset, string localTimeZoneOffset, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; capabilities, class System.Collections.Generic.IList`1&lt;string&gt; serviceUrls, string autoUpdate, string versionStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode},System.Nullable{System.DateTime},System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional state As String = null, Optional createTime As Nullable(Of DateTime) = null, Optional taskQueueId As String = null, Optional internalChannelEncryption As String = null, Optional version As String = null, Optional nodes As IList(Of SelfHostedIntegrationRuntimeNode) = null, Optional scheduledUpdateDate As Nullable(Of DateTime) = null, Optional updateDelayOffset As String = null, Optional localTimeZoneOffset As String = null, Optional capabilities As IDictionary(Of String, String) = null, Optional serviceUrls As IList(Of String) = null, Optional autoUpdate As String = null, Optional versionStatus As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * Nullable&lt;DateTime&gt; * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; * Nullable&lt;DateTime&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus" Usage="new Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus (additionalProperties, state, createTime, taskQueueId, internalChannelEncryption, version, nodes, scheduledUpdateDate, updateDelayOffset, localTimeZoneOffset, capabilities, serviceUrls, autoUpdate, versionStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="createTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="taskQueueId" Type="System.String" />
        <Parameter Name="internalChannelEncryption" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
        <Parameter Name="nodes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;" />
        <Parameter Name="scheduledUpdateDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="updateDelayOffset" Type="System.String" />
        <Parameter Name="localTimeZoneOffset" Type="System.String" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="serviceUrls" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="autoUpdate" Type="System.String" />
        <Parameter Name="versionStatus" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="99242-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="99242-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="state"><span data-ttu-id="99242-104">Der Status der integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="99242-104">The state of integration runtime.</span></span> <span data-ttu-id="99242-105">Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"</span><span class="sxs-lookup"><span data-stu-id="99242-105">Possible values include: 'Initial', 'Stopped', 'Started', 'Starting', 'Stopping', 'NeedRegistration', 'Online', 'Limited', 'Offline'</span></span></param>
        <param name="createTime"><span data-ttu-id="99242-106">Der Zeitpunkt, zu dem der integrationslaufzeit erstellt wurde, im ISO8601-format.</span><span class="sxs-lookup"><span data-stu-id="99242-106">The time at which the integration runtime was created, in ISO8601 format.</span></span></param>
        <param name="taskQueueId"><span data-ttu-id="99242-107">Die Task-Id der Warteschlange von der integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="99242-107">The task queue id of the integration runtime.</span></span></param>
        <param name="internalChannelEncryption"><span data-ttu-id="99242-108">Es wird verwendet, die festzulegende den Verschlüsselungsmodus für Kommunikationskanal zwischen Knoten (Wenn mehr als 2 Integration selbst gehosteten Common Language Runtime-Knoten vorhanden sind).</span><span class="sxs-lookup"><span data-stu-id="99242-108">It is used to set the encryption mode for node-node communication channel (when more than 2 self-hosted integration runtime nodes exist).</span></span> <span data-ttu-id="99242-109">Folgende Werte sind möglich: 'NotSet', 'SslEncrypted', 'NotEncrypted'</span><span class="sxs-lookup"><span data-stu-id="99242-109">Possible values include: 'NotSet', 'SslEncrypted', 'NotEncrypted'</span></span></param>
        <param name="version"><span data-ttu-id="99242-110">Version der Laufzeit der Integration.</span><span class="sxs-lookup"><span data-stu-id="99242-110">Version of the integration runtime.</span></span></param>
        <param name="nodes"><span data-ttu-id="99242-111">Die Liste der Knoten für diese integrationslaufzeit.</span><span class="sxs-lookup"><span data-stu-id="99242-111">The list of nodes for this integration runtime.</span></span></param>
        <param name="scheduledUpdateDate"><span data-ttu-id="99242-112">Das Datum, an dem der integrationslaufzeit geplant wird, um im ISO8601-Format zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="99242-112">The date at which the integration runtime will be scheduled to update, in ISO8601 format.</span></span></param>
        <param name="updateDelayOffset"><span data-ttu-id="99242-113">Die Zeit in das Datum, die vom Dienst zum Aktualisieren von der integrationslaufzeit geplant ist z. B. PT03H 3 Stunden</span><span class="sxs-lookup"><span data-stu-id="99242-113">The time in the date scheduled by service to update the integration runtime, e.g., PT03H is 3 hours</span></span></param>
        <param name="localTimeZoneOffset"><span data-ttu-id="99242-114">Der lokalen Zeitzone in Stunden.</span><span class="sxs-lookup"><span data-stu-id="99242-114">The local time zone offset in hours.</span></span></param>
        <param name="capabilities"><span data-ttu-id="99242-115">Mit zusätzlichen Informationen über Integrationsfunktionen für die Common Language Runtime-Objekt.</span><span class="sxs-lookup"><span data-stu-id="99242-115">Object with additional information about integration runtime capabilities.</span></span></param>
        <param name="serviceUrls"><span data-ttu-id="99242-116">Die URLs für die Dienste, die im Integration Runtime Back-End-Dienst verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="99242-116">The URLs for the services used in integration runtime backend service.</span></span></param>
        <param name="autoUpdate"><span data-ttu-id="99242-117">Gibt an, ob automatische Aktualisierung der Common Language Runtime selbst gehosteten Integration aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="99242-117">Whether Self-hosted integration runtime auto update has been turned on.</span></span> <span data-ttu-id="99242-118">Folgende Werte sind möglich: "On", "deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="99242-118">Possible values include: 'On', 'Off'</span></span></param>
        <param name="versionStatus"><span data-ttu-id="99242-119">Status der Integration Common Language Runtime-Version.</span><span class="sxs-lookup"><span data-stu-id="99242-119">Status of the integration runtime version.</span></span></param>
        <summary>
            <span data-ttu-id="99242-120">Initialisiert eine neue Instanz der SelfHostedIntegrationRuntimeStatus-Klasse.</span><span class="sxs-lookup"><span data-stu-id="99242-120">Initializes a new instance of the SelfHostedIntegrationRuntimeStatus class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoUpdate">
      <MemberSignature Language="C#" Value="public string AutoUpdate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoUpdate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.AutoUpdate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoUpdate As String" />
      <MemberSignature Language="F#" Value="member this.AutoUpdate : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.AutoUpdate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.autoUpdate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-121">Ruft ab, ob die automatische Aktualisierung der Common Language Runtime selbst gehosteten Integration aktiviert wurde.</span><span class="sxs-lookup"><span data-stu-id="99242-121">Gets whether Self-hosted integration runtime auto update has been turned on.</span></span> <span data-ttu-id="99242-122">Folgende Werte sind möglich: "On", "deaktiviert"</span><span class="sxs-lookup"><span data-stu-id="99242-122">Possible values include: 'On', 'Off'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-123">Ruft-Objekt mit zusätzlichen Informationen über die Common Language Runtime-Integrationsfunktionen.</span><span class="sxs-lookup"><span data-stu-id="99242-123">Gets object with additional information about integration runtime capabilities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.CreateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreateTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.CreateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.createTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-124">Ruft den Zeitpunkt, zu dem der integrationslaufzeit im ISO8601-Format erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="99242-124">Gets the time at which the integration runtime was created, in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalChannelEncryption">
      <MemberSignature Language="C#" Value="public string InternalChannelEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalChannelEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.InternalChannelEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InternalChannelEncryption As String" />
      <MemberSignature Language="F#" Value="member this.InternalChannelEncryption : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.InternalChannelEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.internalChannelEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-125">Ruft ab, die sie mit den Verschlüsselungsmodus für Kommunikationskanal zwischen Knoten festgelegt wird (Wenn mehr als 2 Integration selbst gehosteten Common Language Runtime-Knoten vorhanden sind).</span><span class="sxs-lookup"><span data-stu-id="99242-125">Gets it is used to set the encryption mode for node-node communication channel (when more than 2 self-hosted integration runtime nodes exist).</span></span> <span data-ttu-id="99242-126">Folgende Werte sind möglich: 'NotSet', 'SslEncrypted', 'NotEncrypted'</span><span class="sxs-lookup"><span data-stu-id="99242-126">Possible values include: 'NotSet', 'SslEncrypted', 'NotEncrypted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalTimeZoneOffset">
      <MemberSignature Language="C#" Value="public string LocalTimeZoneOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalTimeZoneOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.LocalTimeZoneOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalTimeZoneOffset As String" />
      <MemberSignature Language="F#" Value="member this.LocalTimeZoneOffset : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.LocalTimeZoneOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.localTimeZoneOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-127">Ruft den Offset der Ortszeit Zone in Stunden ab.</span><span class="sxs-lookup"><span data-stu-id="99242-127">Gets the local time zone offset in hours.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; Nodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public Property Nodes As IList(Of SelfHostedIntegrationRuntimeNode)" />
      <MemberSignature Language="F#" Value="member this.Nodes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.nodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeNode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-128">Ruft ab oder legt die Liste der Knoten für diese integrationslaufzeit fest.</span><span class="sxs-lookup"><span data-stu-id="99242-128">Gets or sets the list of nodes for this integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduledUpdateDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ScheduledUpdateDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ScheduledUpdateDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.ScheduledUpdateDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScheduledUpdateDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ScheduledUpdateDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.ScheduledUpdateDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.scheduledUpdateDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-129">Ruft das Datum, an dem der integrationslaufzeit geplant wird, um im ISO8601-Format zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="99242-129">Gets the date at which the integration runtime will be scheduled to update, in ISO8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceUrls">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ServiceUrls { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ServiceUrls" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.ServiceUrls" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceUrls As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ServiceUrls : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.ServiceUrls" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.serviceUrls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-130">Ruft die URLs für die Dienste, die im Integration Runtime Back-End-Dienst verwendet.</span><span class="sxs-lookup"><span data-stu-id="99242-130">Gets the URLs for the services used in integration runtime backend service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskQueueId">
      <MemberSignature Language="C#" Value="public string TaskQueueId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskQueueId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.TaskQueueId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskQueueId As String" />
      <MemberSignature Language="F#" Value="member this.TaskQueueId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.TaskQueueId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.taskQueueId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-131">Ruft die Task-Warteschlangen-Id von der integrationslaufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="99242-131">Gets the task queue id of the integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDelayOffset">
      <MemberSignature Language="C#" Value="public string UpdateDelayOffset { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpdateDelayOffset" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.UpdateDelayOffset" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpdateDelayOffset As String" />
      <MemberSignature Language="F#" Value="member this.UpdateDelayOffset : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.UpdateDelayOffset" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.updateDelayOffset")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-132">Ruft die Zeit in das Datum, die vom Dienst zum Aktualisieren von der integrationslaufzeit, z. B. PT03H geplant beträgt 3 Stunden</span><span class="sxs-lookup"><span data-stu-id="99242-132">Gets the time in the date scheduled by service to update the integration runtime, e.g., PT03H is 3 hours</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Version">
      <MemberSignature Language="C#" Value="public string Version { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Version" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Version" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Version As String" />
      <MemberSignature Language="F#" Value="member this.Version : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.Version" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.version")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-133">Ruft die Version von der integrationslaufzeit ab.</span><span class="sxs-lookup"><span data-stu-id="99242-133">Gets version of the integration runtime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VersionStatus">
      <MemberSignature Language="C#" Value="public string VersionStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VersionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.VersionStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VersionStatus As String" />
      <MemberSignature Language="F#" Value="member this.VersionStatus : string" Usage="Microsoft.Azure.Management.DataFactory.Models.SelfHostedIntegrationRuntimeStatus.VersionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.versionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99242-134">Ruft die Laufzeitversion Integration Status ab.</span><span class="sxs-lookup"><span data-stu-id="99242-134">Gets status of the integration runtime version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>