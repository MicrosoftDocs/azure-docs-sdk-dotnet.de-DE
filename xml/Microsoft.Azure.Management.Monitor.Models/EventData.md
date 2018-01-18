<Type Name="EventData" FullName="Microsoft.Azure.Management.Monitor.Models.EventData">
  <TypeSignature Language="C#" Value="public class EventData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.EventData" />
  <TypeSignature Language="VB.NET" Value="Public Class EventData" />
  <TypeSignature Language="F#" Value="type EventData = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0fac2-101">Die Azure Ereignisprotokolleinträge sind vom Typ EventData</span><span class="sxs-lookup"><span data-stu-id="0fac2-101">The Azure event log entries are of type EventData</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-102">Initialisiert eine neue Instanz der EventData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0fac2-102">Initializes a new instance of the EventData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventData (Microsoft.Azure.Management.Monitor.Models.EventLevel level, DateTime eventTimestamp, DateTime submissionTimestamp, Microsoft.Azure.Management.Monitor.Models.SenderAuthorization authorization = null, System.Collections.Generic.IDictionary&lt;string,string&gt; claims = null, string caller = null, string description = null, string id = null, string eventDataId = null, string correlationId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString eventName = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString category = null, Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo httpRequest = null, string resourceGroupName = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceProviderName = null, string resourceId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceType = null, string operationId = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString operationName = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString status = null, Microsoft.Azure.Management.Monitor.Models.LocalizableString subStatus = null, string subscriptionId = null, string tenantId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Monitor.Models.EventLevel level, valuetype System.DateTime eventTimestamp, valuetype System.DateTime submissionTimestamp, class Microsoft.Azure.Management.Monitor.Models.SenderAuthorization authorization, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; claims, string caller, string description, string id, string eventDataId, string correlationId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString eventName, class Microsoft.Azure.Management.Monitor.Models.LocalizableString category, class Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo httpRequest, string resourceGroupName, class Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceProviderName, string resourceId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString resourceType, string operationId, class Microsoft.Azure.Management.Monitor.Models.LocalizableString operationName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class Microsoft.Azure.Management.Monitor.Models.LocalizableString status, class Microsoft.Azure.Management.Monitor.Models.LocalizableString subStatus, string subscriptionId, string tenantId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.#ctor(Microsoft.Azure.Management.Monitor.Models.EventLevel,System.DateTime,System.DateTime,Microsoft.Azure.Management.Monitor.Models.SenderAuthorization,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.LocalizableString,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (level As EventLevel, eventTimestamp As DateTime, submissionTimestamp As DateTime, Optional authorization As SenderAuthorization = null, Optional claims As IDictionary(Of String, String) = null, Optional caller As String = null, Optional description As String = null, Optional id As String = null, Optional eventDataId As String = null, Optional correlationId As String = null, Optional eventName As LocalizableString = null, Optional category As LocalizableString = null, Optional httpRequest As HttpRequestInfo = null, Optional resourceGroupName As String = null, Optional resourceProviderName As LocalizableString = null, Optional resourceId As String = null, Optional resourceType As LocalizableString = null, Optional operationId As String = null, Optional operationName As LocalizableString = null, Optional properties As IDictionary(Of String, String) = null, Optional status As LocalizableString = null, Optional subStatus As LocalizableString = null, Optional subscriptionId As String = null, Optional tenantId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.EventData : Microsoft.Azure.Management.Monitor.Models.EventLevel * DateTime * DateTime * Microsoft.Azure.Management.Monitor.Models.SenderAuthorization * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * string * string * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.LocalizableString * string * string -&gt; Microsoft.Azure.Management.Monitor.Models.EventData" Usage="new Microsoft.Azure.Management.Monitor.Models.EventData (level, eventTimestamp, submissionTimestamp, authorization, claims, caller, description, id, eventDataId, correlationId, eventName, category, httpRequest, resourceGroupName, resourceProviderName, resourceId, resourceType, operationId, operationName, properties, status, subStatus, subscriptionId, tenantId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="level" Type="Microsoft.Azure.Management.Monitor.Models.EventLevel" />
        <Parameter Name="eventTimestamp" Type="System.DateTime" />
        <Parameter Name="submissionTimestamp" Type="System.DateTime" />
        <Parameter Name="authorization" Type="Microsoft.Azure.Management.Monitor.Models.SenderAuthorization" />
        <Parameter Name="claims" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="caller" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="eventDataId" Type="System.String" />
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="eventName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="category" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="httpRequest" Type="Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="resourceType" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="operationId" Type="System.String" />
        <Parameter Name="operationName" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="status" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="subStatus" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="tenantId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="0fac2-103">die Ereignisebene.</span><span class="sxs-lookup"><span data-stu-id="0fac2-103">the event level.</span></span> <span data-ttu-id="0fac2-104">Folgende Werte sind möglich: "Kritisch", "Fehler", "Warnung", "Information", "Verbose"</span><span class="sxs-lookup"><span data-stu-id="0fac2-104">Possible values include: 'Critical', 'Error', 'Warning', 'Informational', 'Verbose'</span></span></param>
        <param name="eventTimestamp"><span data-ttu-id="0fac2-105">der Timestamp der das Ereignis von der Azure-Dienst Verarbeiten der Anforderung entspricht das Ereignis generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="0fac2-105">the timestamp of when the event was generated by the Azure service processing the request corresponding the event.</span></span> <span data-ttu-id="0fac2-106">Es im ISO 8601-Format.</span><span class="sxs-lookup"><span data-stu-id="0fac2-106">It in ISO 8601 format.</span></span></param>
        <param name="submissionTimestamp"><span data-ttu-id="0fac2-107">der Timestamp der, wenn das Ereignis für die Abfrage über diese API verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="0fac2-107">the timestamp of when the event became available for querying via this API.</span></span> <span data-ttu-id="0fac2-108">Es ist im ISO 8601-Format.</span><span class="sxs-lookup"><span data-stu-id="0fac2-108">It is in ISO 8601 format.</span></span> <span data-ttu-id="0fac2-109">Dieser Wert darf nicht zu verwechseln EventTimestamp sein.</span><span class="sxs-lookup"><span data-stu-id="0fac2-109">This value should not be confused eventTimestamp.</span></span> <span data-ttu-id="0fac2-110">Da es möglicherweise eine Verzögerung zwischen dem Zeitpunkt des Auftretens des Ereignisses und die Zeit, die das Ereignis an den Azure Protokollierungsinfrastruktur gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0fac2-110">As there might be a delay between the occurrence time of the event, and the time that the event is submitted to the Azure logging infrastructure.</span></span></param>
        <param name="authorization">To be added.</param>
        <param name="claims"><span data-ttu-id="0fac2-111">Schlüssel-Wert-Paare zum Identifizieren von ARM-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="0fac2-111">key value pairs to identify ARM permissions.</span></span></param>
        <param name="caller"><span data-ttu-id="0fac2-112">die e-Mail-Adresse des Benutzers, der den Vorgang, den Anspruch der UPN oder SPN-Anspruch auf Grundlage der Verfügbarkeit ausgeführt hat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-112">the email address of the user who has performed the operation, the UPN claim or SPN claim based on availability.</span></span></param>
        <param name="description"><span data-ttu-id="0fac2-113">die Beschreibung des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="0fac2-113">the description of the event.</span></span></param>
        <param name="id"><span data-ttu-id="0fac2-114">die Id dieses Ereignisses ARM für RBAC erforderlich.</span><span class="sxs-lookup"><span data-stu-id="0fac2-114">the Id of this event as required by ARM for RBAC.</span></span>
            <span data-ttu-id="0fac2-115">Außerdem enthält die EventDataID sowie eine Timestampinformationen.</span><span class="sxs-lookup"><span data-stu-id="0fac2-115">It contains the EventDataID and a timestamp information.</span></span></param>
        <param name="eventDataId"><span data-ttu-id="0fac2-116">die Ereignisdaten Id. Dies ist ein eindeutiger Bezeichner für ein Ereignis.</span><span class="sxs-lookup"><span data-stu-id="0fac2-116">the event data Id. This is a unique identifier for an event.</span></span></param>
        <param name="correlationId"><span data-ttu-id="0fac2-117">die Korrelations-Id in der Regel eine GUID im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-117">the correlation Id, usually a GUID in the string format.</span></span> <span data-ttu-id="0fac2-118">Die Korrelations-Id wird von den Ereignissen gemeinsam genutzt, die auf den gleichen Uber Vorgang gehören.</span><span class="sxs-lookup"><span data-stu-id="0fac2-118">The correlation Id is shared among the events that belong to the same uber operation.</span></span></param>
        <param name="eventName"><span data-ttu-id="0fac2-119">der Name des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="0fac2-119">the event name.</span></span> <span data-ttu-id="0fac2-120">Dieser Wert sollte nicht mit OperationName verwechselt werden.</span><span class="sxs-lookup"><span data-stu-id="0fac2-120">This value should not be confused with OperationName.</span></span> <span data-ttu-id="0fac2-121">Aus praktischen Gründen möglicherweise OperationName ansprechender für Endbenutzer.</span><span class="sxs-lookup"><span data-stu-id="0fac2-121">For practical purposes, OperationName might be more appealing to end users.</span></span></param>
        <param name="category"><span data-ttu-id="0fac2-122">die Ereigniskategorie.</span><span class="sxs-lookup"><span data-stu-id="0fac2-122">the event category.</span></span></param>
        <param name="httpRequest"><span data-ttu-id="0fac2-123">die Informationen für den HTTP-Anforderung.</span><span class="sxs-lookup"><span data-stu-id="0fac2-123">the HTTP request info.</span></span> <span data-ttu-id="0fac2-124">In der Regel umfasst "ClientRequestId", "ClientIpAddress" (IP-Adresse des Benutzers, der das Ereignis initiiert hat) und "Method" (HTTP-Methode, z. B. PUT).</span><span class="sxs-lookup"><span data-stu-id="0fac2-124">Usually includes the 'clientRequestId', 'clientIpAddress' (IP address of the user who initiated the event) and 'method' (HTTP method e.g. PUT).</span></span></param>
        <param name="resourceGroupName"><span data-ttu-id="0fac2-125">der Ressourcengruppenname der betroffenen Ressource.</span><span class="sxs-lookup"><span data-stu-id="0fac2-125">the resource group name of the impacted resource.</span></span></param>
        <param name="resourceProviderName"><span data-ttu-id="0fac2-126">der Ressourcenname des Anbieters der betroffenen Ressource.</span><span class="sxs-lookup"><span data-stu-id="0fac2-126">the resource provider name of the impacted resource.</span></span></param>
        <param name="resourceId"><span data-ttu-id="0fac2-127">der Ressourcen-Uri, der die Ressource eindeutig identifiziert wird, die dieses Ereignis verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-127">the resource uri that uniquely identifies the resource that caused this event.</span></span></param>
        <param name="resourceType"><span data-ttu-id="0fac2-128">der Ressourcentyp ""</span><span class="sxs-lookup"><span data-stu-id="0fac2-128">the resource type</span></span></param>
        <param name="operationId"><span data-ttu-id="0fac2-129">Es ist normalerweise eine GUID, die für die einzelnen Vorgang entsprechen, Ereignisse gemeinsam verwendet.</span><span class="sxs-lookup"><span data-stu-id="0fac2-129">It is usually a GUID shared among the events corresponding to single operation.</span></span> <span data-ttu-id="0fac2-130">Dieser Wert sollte nicht mit EventName verwechselt werden.</span><span class="sxs-lookup"><span data-stu-id="0fac2-130">This value should not be confused with EventName.</span></span></param>
        <param name="operationName"><span data-ttu-id="0fac2-131">Der Name des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="0fac2-131">the operation name.</span></span></param>
        <param name="properties"><span data-ttu-id="0fac2-132">der Satz von &lt;Schlüssel, Wert&gt; Paare (normalerweise ein Wörterbuch&lt;String, String&gt;), die Details zum Ereignis enthält.</span><span class="sxs-lookup"><span data-stu-id="0fac2-132">the set of &lt;Key, Value&gt; pairs (usually a Dictionary&lt;String, String&gt;) that includes details about the event.</span></span></param>
        <param name="status"><span data-ttu-id="0fac2-133">eine Zeichenfolge, die den Status des Vorgangs beschreibt.</span><span class="sxs-lookup"><span data-stu-id="0fac2-133">a string describing the status of the operation.</span></span> <span data-ttu-id="0fac2-134">Einige typische Werte sind: gestartet, ausgeführt wird, erfolgreich "," Fehler "und" aufgelöst.</span><span class="sxs-lookup"><span data-stu-id="0fac2-134">Some typical values are: Started, In progress, Succeeded, Failed, Resolved.</span></span></param>
        <param name="subStatus"><span data-ttu-id="0fac2-135">der Status des Sub.</span><span class="sxs-lookup"><span data-stu-id="0fac2-135">the event sub status.</span></span> <span data-ttu-id="0fac2-136">Die meisten der Zeit, wenn enthalten, zeichnet den HTTP-Statuscode des REST-Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="0fac2-136">Most of the time, when included, this captures the HTTP status code of the REST call.</span></span>
            <span data-ttu-id="0fac2-137">Häufig verwendete Werte sind: OK (HTTP-Statuscode: 200) erstelltes (HTTP-Statuscode: 201), akzeptiert (HTTP-Statuscode: 202), No Content (HTTP-Statuscode: 204), fehlerhafte Request(HTTP Status Code: 400), wurde Nichtgefunden (HTTP-Statuscode: 404), Konflikt (HTTP-Statuscode:: 409), interne Serverfehler (HTTP-Statuscode: 500), der Dienst ist nicht verfügbar (HTTP-Statuscode: 503), GatewayTimeout (HTTP-Statuscode: 504)</span><span class="sxs-lookup"><span data-stu-id="0fac2-137">Common values are: OK (HTTP Status Code: 200), Created (HTTP Status Code: 201), Accepted (HTTP Status Code: 202), No Content (HTTP Status Code: 204), Bad Request(HTTP Status Code: 400), Not Found (HTTP Status Code: 404), Conflict (HTTP Status Code: 409), Internal Server Error (HTTP Status Code: 500), Service Unavailable (HTTP Status Code:503), Gateway Timeout (HTTP Status Code: 504)</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="0fac2-138">die Azure-Abonnement-Id in der Regel eine GUID.</span><span class="sxs-lookup"><span data-stu-id="0fac2-138">the Azure subscription Id usually a GUID.</span></span></param>
        <param name="tenantId"><span data-ttu-id="0fac2-139">der Azure-Mandanten-Id</span><span class="sxs-lookup"><span data-stu-id="0fac2-139">the Azure tenant Id</span></span></param>
        <summary>
            <span data-ttu-id="0fac2-140">Initialisiert eine neue Instanz der EventData-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0fac2-140">Initializes a new instance of the EventData class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authorization">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.SenderAuthorization Authorization { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.SenderAuthorization Authorization" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Authorization" />
      <MemberSignature Language="VB.NET" Value="Public Property Authorization As SenderAuthorization" />
      <MemberSignature Language="F#" Value="member this.Authorization : Microsoft.Azure.Management.Monitor.Models.SenderAuthorization with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Authorization" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorization")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.SenderAuthorization</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caller">
      <MemberSignature Language="C#" Value="public string Caller { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Caller" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Caller" />
      <MemberSignature Language="VB.NET" Value="Public Property Caller As String" />
      <MemberSignature Language="F#" Value="member this.Caller : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Caller" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caller")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-141">Ruft ab oder legt die e-Mail-Adresse des Benutzers, der den Vorgang, den Anspruch der UPN oder SPN-Anspruch auf Grundlage der Verfügbarkeit ausgeführt hat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-141">Gets or sets the email address of the user who has performed the operation, the UPN claim or SPN claim based on availability.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Category : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-142">Ruft ab oder legt die Ereigniskategorie.</span><span class="sxs-lookup"><span data-stu-id="0fac2-142">Gets or sets the event category.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Claims">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Claims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Claims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Claims" />
      <MemberSignature Language="VB.NET" Value="Public Property Claims As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Claims : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Claims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="claims")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-143">Abrufen oder Festlegen der Schlüssel-Wert-Paare zum Identifizieren von ARM-Berechtigungen.</span><span class="sxs-lookup"><span data-stu-id="0fac2-143">Gets or sets key value pairs to identify ARM permissions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-144">Ruft ab oder legt die Korrelations-Id in der Regel eine GUID im Zeichenfolgenformat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-144">Gets or sets the correlation Id, usually a GUID in the string format.</span></span> <span data-ttu-id="0fac2-145">Die Korrelations-Id wird von den Ereignissen gemeinsam genutzt, die auf den gleichen Uber Vorgang gehören.</span><span class="sxs-lookup"><span data-stu-id="0fac2-145">The correlation Id is shared among the events that belong to the same uber operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            <span data-ttu-id="0fac2-146">Ruft ab oder legt die Beschreibung des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="0fac2-146">Gets or sets the description of the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventDataId">
      <MemberSignature Language="C#" Value="public string EventDataId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventDataId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventDataId" />
      <MemberSignature Language="VB.NET" Value="Public Property EventDataId As String" />
      <MemberSignature Language="F#" Value="member this.EventDataId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventDataId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventDataId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-147">Ruft ab oder legt die Ereignisdaten Id. Dies ist ein eindeutiger Bezeichner für ein Ereignis.</span><span class="sxs-lookup"><span data-stu-id="0fac2-147">Gets or sets the event data Id. This is a unique identifier for an event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString EventName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString EventName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.EventName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-148">Ruft ab oder legt den Namen des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="0fac2-148">Gets or sets the event name.</span></span> <span data-ttu-id="0fac2-149">Dieser Wert sollte nicht mit OperationName verwechselt werden.</span><span class="sxs-lookup"><span data-stu-id="0fac2-149">This value should not be confused with OperationName.</span></span> <span data-ttu-id="0fac2-150">Aus praktischen Gründen möglicherweise OperationName ansprechender für Endbenutzer.</span><span class="sxs-lookup"><span data-stu-id="0fac2-150">For practical purposes, OperationName might be more appealing to end users.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventTimestamp">
      <MemberSignature Language="C#" Value="public DateTime EventTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EventTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.EventTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property EventTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.EventTimestamp : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.EventTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-151">Ruft ab oder legt den Zeitstempel des fest, wenn das Ereignis von der Azure-Dienst Verarbeiten der Anforderung entspricht das Ereignis generiert wurde.</span><span class="sxs-lookup"><span data-stu-id="0fac2-151">Gets or sets the timestamp of when the event was generated by the Azure service processing the request corresponding the event.</span></span> <span data-ttu-id="0fac2-152">Es im ISO 8601-Format.</span><span class="sxs-lookup"><span data-stu-id="0fac2-152">It in ISO 8601 format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpRequest">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo HttpRequest { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo HttpRequest" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.HttpRequest" />
      <MemberSignature Language="VB.NET" Value="Public Property HttpRequest As HttpRequestInfo" />
      <MemberSignature Language="F#" Value="member this.HttpRequest : Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.HttpRequest" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="httpRequest")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.HttpRequestInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-153">Ruft ab oder legt den HTTP-Anforderung Info.</span><span class="sxs-lookup"><span data-stu-id="0fac2-153">Gets or sets the HTTP request info.</span></span> <span data-ttu-id="0fac2-154">In der Regel umfasst "ClientRequestId", "ClientIpAddress" (IP-Adresse des Benutzers, der das Ereignis initiiert hat) und "Method" (HTTP-Methode, z. B. PUT).</span><span class="sxs-lookup"><span data-stu-id="0fac2-154">Usually includes the 'clientRequestId', 'clientIpAddress' (IP address of the user who initiated the event) and 'method' (HTTP method e.g. PUT).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-155">Ruft ab oder legt die Id dieses Ereignisses gemäß ARM für RBAC.</span><span class="sxs-lookup"><span data-stu-id="0fac2-155">Gets or sets the Id of this event as required by ARM for RBAC.</span></span> <span data-ttu-id="0fac2-156">Außerdem enthält die EventDataID sowie eine Timestampinformationen.</span><span class="sxs-lookup"><span data-stu-id="0fac2-156">It contains the EventDataID and a timestamp information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.EventLevel Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Models.EventLevel Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As EventLevel" />
      <MemberSignature Language="F#" Value="member this.Level : Microsoft.Azure.Management.Monitor.Models.EventLevel with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.EventLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-157">Ruft ab oder legt fest, Ereignis.</span><span class="sxs-lookup"><span data-stu-id="0fac2-157">Gets or sets the event level.</span></span> <span data-ttu-id="0fac2-158">Folgende Werte sind möglich: "Kritisch", "Fehler", "Warnung", "Information", "Verbose"</span><span class="sxs-lookup"><span data-stu-id="0fac2-158">Possible values include: 'Critical', 'Error', 'Warning', 'Informational', 'Verbose'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public string OperationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OperationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationId As String" />
      <MemberSignature Language="F#" Value="member this.OperationId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-159">Ruft ab oder legt ihn fest, die sie in der Regel ist eine GUID, die für die Ereignisse, die einzelnen Vorgang entsprechen, freigegeben werden.</span><span class="sxs-lookup"><span data-stu-id="0fac2-159">Gets or sets it is usually a GUID shared among the events corresponding to single operation.</span></span> <span data-ttu-id="0fac2-160">Dieser Wert sollte nicht mit EventName verwechselt werden.</span><span class="sxs-lookup"><span data-stu-id="0fac2-160">This value should not be confused with EventName.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString OperationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString OperationName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.OperationName" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.OperationName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.OperationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-161">Ruft ab oder legt den Vorgangsnamen fest.</span><span class="sxs-lookup"><span data-stu-id="0fac2-161">Gets or sets the operation name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-162">Ruft ab oder legt sie fest &amp;Lt; Schlüssel, Wert&amp;Gt; Paare (normalerweise ein Wörterbuch&amp;Lt; String, String&amp;Gt;), die Details zum Ereignis enthält.</span><span class="sxs-lookup"><span data-stu-id="0fac2-162">Gets or sets the set of &amp;lt;Key, Value&amp;gt; pairs (usually a Dictionary&amp;lt;String, String&amp;gt;) that includes details about the event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroupName">
      <MemberSignature Language="C#" Value="public string ResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-163">Ruft ab oder legt der Ressourcengruppenname der betroffenen Ressource.</span><span class="sxs-lookup"><span data-stu-id="0fac2-163">Gets or sets the resource group name of the impacted resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-164">Abrufen oder Festlegen der Ressourcen-Uri, der die Ressource eindeutig identifiziert wird, die dieses Ereignis verursacht hat.</span><span class="sxs-lookup"><span data-stu-id="0fac2-164">Gets or sets the resource uri that uniquely identifies the resource that caused this event.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceProviderName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceProviderName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceProviderName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceProviderName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceProviderName As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.ResourceProviderName : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceProviderName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceProviderName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-165">Ruft ab oder legt die ressourcenanbietername der betroffenen Ressource.</span><span class="sxs-lookup"><span data-stu-id="0fac2-165">Gets or sets the resource provider name of the impacted resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceType As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.ResourceType : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-166">Ruft ab oder legt den Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="0fac2-166">Gets or sets the resource type</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-167">Ruft ab oder legt eine Zeichenfolge, die den Status des Vorgangs fest.</span><span class="sxs-lookup"><span data-stu-id="0fac2-167">Gets or sets a string describing the status of the operation.</span></span> <span data-ttu-id="0fac2-168">Einige typische Werte sind: gestartet, ausgeführt wird, erfolgreich "," Fehler "und" aufgelöst.</span><span class="sxs-lookup"><span data-stu-id="0fac2-168">Some typical values are: Started, In progress, Succeeded, Failed, Resolved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmissionTimestamp">
      <MemberSignature Language="C#" Value="public DateTime SubmissionTimestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime SubmissionTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubmissionTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property SubmissionTimestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.SubmissionTimestamp : DateTime with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubmissionTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="submissionTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-169">Ruft ab oder legt den Zeitstempel des fest, wenn das Ereignis für die Abfrage über diese API verfügbar war.</span><span class="sxs-lookup"><span data-stu-id="0fac2-169">Gets or sets the timestamp of when the event became available for querying via this API.</span></span> <span data-ttu-id="0fac2-170">Es ist im ISO 8601-Format.</span><span class="sxs-lookup"><span data-stu-id="0fac2-170">It is in ISO 8601 format.</span></span> <span data-ttu-id="0fac2-171">Dieser Wert darf nicht zu verwechseln EventTimestamp sein.</span><span class="sxs-lookup"><span data-stu-id="0fac2-171">This value should not be confused eventTimestamp.</span></span> <span data-ttu-id="0fac2-172">Da es möglicherweise eine Verzögerung zwischen dem Zeitpunkt des Auftretens des Ereignisses und die Zeit, die das Ereignis an den Azure Protokollierungsinfrastruktur gesendet wird.</span><span class="sxs-lookup"><span data-stu-id="0fac2-172">As there might be a delay between the occurrence time of the event, and the time that the event is submitted to the Azure logging infrastructure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-173">Ruft ab oder legt dem Azure-Abonnement-Id in der Regel eine GUID.</span><span class="sxs-lookup"><span data-stu-id="0fac2-173">Gets or sets the Azure subscription Id usually a GUID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString SubStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString SubStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.SubStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property SubStatus As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.SubStatus : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.SubStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-174">Ermittelt oder der Ereignisstatus Sub definiert.</span><span class="sxs-lookup"><span data-stu-id="0fac2-174">Gets or sets the event sub status.</span></span> <span data-ttu-id="0fac2-175">Die meisten der Zeit, wenn enthalten, zeichnet den HTTP-Statuscode des REST-Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="0fac2-175">Most of the time, when included, this captures the HTTP status code of the REST call.</span></span> <span data-ttu-id="0fac2-176">Häufig verwendete Werte sind: OK (HTTP-Statuscode: 200) erstelltes (HTTP-Statuscode: 201), akzeptiert (HTTP-Statuscode: 202), No Content (HTTP-Statuscode: 204), fehlerhafte Request(HTTP Status Code: 400), wurde Nichtgefunden (HTTP-Statuscode: 404), Konflikt (HTTP-Statuscode:: 409), interne Serverfehler (HTTP-Statuscode: 500), der Dienst ist nicht verfügbar (HTTP-Statuscode: 503), GatewayTimeout (HTTP-Statuscode: 504)</span><span class="sxs-lookup"><span data-stu-id="0fac2-176">Common values are: OK (HTTP Status Code: 200), Created (HTTP Status Code: 201), Accepted (HTTP Status Code: 202), No Content (HTTP Status Code: 204), Bad Request(HTTP Status Code: 400), Not Found (HTTP Status Code: 404), Conflict (HTTP Status Code: 409), Internal Server Error (HTTP Status Code: 500), Service Unavailable (HTTP Status Code:503), Gateway Timeout (HTTP Status Code: 504)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public string TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.EventData.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As String" />
      <MemberSignature Language="F#" Value="member this.TenantId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.EventData.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-177">Ruft ab oder legt den Azure-Mandanten-Id</span><span class="sxs-lookup"><span data-stu-id="0fac2-177">Gets or sets the Azure tenant Id</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.EventData.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="eventData.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0fac2-178">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="0fac2-178">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="0fac2-179">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="0fac2-179">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>