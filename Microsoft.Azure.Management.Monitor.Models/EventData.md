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
            Die Azure Ereignisprotokolleinträge sind vom Typ EventData
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
            Initialisiert eine neue Instanz der EventData-Klasse.
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
        <param name="level">die Ereignisebene. Folgende Werte sind möglich: "Kritisch", "Fehler", "Warnung", "Information", "Verbose"</param>
        <param name="eventTimestamp">der Timestamp der das Ereignis von der Azure-Dienst Verarbeiten der Anforderung entspricht das Ereignis generiert wurde. Es im ISO 8601-Format.</param>
        <param name="submissionTimestamp">der Timestamp der, wenn das Ereignis für die Abfrage über diese API verfügbar war. Es ist im ISO 8601-Format. Dieser Wert darf nicht zu verwechseln EventTimestamp sein. Da es möglicherweise eine Verzögerung zwischen dem Zeitpunkt des Auftretens des Ereignisses und die Zeit, die das Ereignis an den Azure Protokollierungsinfrastruktur gesendet wird.</param>
        <param name="authorization">To be added.</param>
        <param name="claims">Schlüssel-Wert-Paare zum Identifizieren von ARM-Berechtigungen.</param>
        <param name="caller">die e-Mail-Adresse des Benutzers, der den Vorgang, den Anspruch der UPN oder SPN-Anspruch auf Grundlage der Verfügbarkeit ausgeführt hat.</param>
        <param name="description">die Beschreibung des Ereignisses.</param>
        <param name="id">die Id dieses Ereignisses ARM für RBAC erforderlich.
            Außerdem enthält die EventDataID sowie eine Timestampinformationen.</param>
        <param name="eventDataId">die Ereignisdaten Id. Dies ist ein eindeutiger Bezeichner für ein Ereignis.</param>
        <param name="correlationId">die Korrelations-Id in der Regel eine GUID im Zeichenfolgenformat. Die Korrelations-Id wird von den Ereignissen gemeinsam genutzt, die auf den gleichen Uber Vorgang gehören.</param>
        <param name="eventName">der Name des Ereignisses. Dieser Wert sollte nicht mit OperationName verwechselt werden. Aus praktischen Gründen möglicherweise OperationName ansprechender für Endbenutzer.</param>
        <param name="category">die Ereigniskategorie.</param>
        <param name="httpRequest">die Informationen für den HTTP-Anforderung. In der Regel umfasst "ClientRequestId", "ClientIpAddress" (IP-Adresse des Benutzers, der das Ereignis initiiert hat) und "Method" (HTTP-Methode, z. B. PUT).</param>
        <param name="resourceGroupName">der Ressourcengruppenname der betroffenen Ressource.</param>
        <param name="resourceProviderName">der Ressourcenname des Anbieters der betroffenen Ressource.</param>
        <param name="resourceId">der Ressourcen-Uri, der die Ressource eindeutig identifiziert wird, die dieses Ereignis verursacht hat.</param>
        <param name="resourceType">der Ressourcentyp ""</param>
        <param name="operationId">Es ist normalerweise eine GUID, die für die einzelnen Vorgang entsprechen, Ereignisse gemeinsam verwendet. Dieser Wert sollte nicht mit EventName verwechselt werden.</param>
        <param name="operationName">Der Name des Vorgangs.</param>
        <param name="properties">der Satz von &lt;Schlüssel, Wert&gt; Paare (normalerweise ein Wörterbuch&lt;String, String&gt;), die Details zum Ereignis enthält.</param>
        <param name="status">eine Zeichenfolge, die den Status des Vorgangs beschreibt. Einige typische Werte sind: gestartet, ausgeführt wird, erfolgreich "," Fehler "und" aufgelöst.</param>
        <param name="subStatus">der Status des Sub. Die meisten der Zeit, wenn enthalten, zeichnet den HTTP-Statuscode des REST-Aufrufs.
            Häufig verwendete Werte sind: OK (HTTP-Statuscode: 200) erstelltes (HTTP-Statuscode: 201), akzeptiert (HTTP-Statuscode: 202), No Content (HTTP-Statuscode: 204), fehlerhafte Request(HTTP Status Code: 400), wurde Nichtgefunden (HTTP-Statuscode: 404), Konflikt (HTTP-Statuscode:: 409), interne Serverfehler (HTTP-Statuscode: 500), der Dienst ist nicht verfügbar (HTTP-Statuscode: 503), GatewayTimeout (HTTP-Statuscode: 504)</param>
        <param name="subscriptionId">die Azure-Abonnement-Id in der Regel eine GUID.</param>
        <param name="tenantId">der Azure-Mandanten-Id</param>
        <summary>
            Initialisiert eine neue Instanz der EventData-Klasse.
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
            Ruft ab oder legt die e-Mail-Adresse des Benutzers, der den Vorgang, den Anspruch der UPN oder SPN-Anspruch auf Grundlage der Verfügbarkeit ausgeführt hat.
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
            Ruft ab oder legt die Ereigniskategorie.
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
            Abrufen oder Festlegen der Schlüssel-Wert-Paare zum Identifizieren von ARM-Berechtigungen.
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
            Ruft ab oder legt die Korrelations-Id in der Regel eine GUID im Zeichenfolgenformat. Die Korrelations-Id wird von den Ereignissen gemeinsam genutzt, die auf den gleichen Uber Vorgang gehören.
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
            Ruft ab oder legt die Beschreibung des Ereignisses.
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
            Ruft ab oder legt die Ereignisdaten Id. Dies ist ein eindeutiger Bezeichner für ein Ereignis.
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
            Ruft ab oder legt den Namen des Ereignisses. Dieser Wert sollte nicht mit OperationName verwechselt werden. Aus praktischen Gründen möglicherweise OperationName ansprechender für Endbenutzer.
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
            Ruft ab oder legt den Zeitstempel des fest, wenn das Ereignis von der Azure-Dienst Verarbeiten der Anforderung entspricht das Ereignis generiert wurde. Es im ISO 8601-Format.
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
            Ruft ab oder legt den HTTP-Anforderung Info. In der Regel umfasst "ClientRequestId", "ClientIpAddress" (IP-Adresse des Benutzers, der das Ereignis initiiert hat) und "Method" (HTTP-Methode, z. B. PUT).
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
            Ruft ab oder legt die Id dieses Ereignisses gemäß ARM für RBAC. Außerdem enthält die EventDataID sowie eine Timestampinformationen.
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
            Ruft ab oder legt fest, Ereignis. Folgende Werte sind möglich: "Kritisch", "Fehler", "Warnung", "Information", "Verbose"
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
            Ruft ab oder legt ihn fest, die sie in der Regel ist eine GUID, die für die Ereignisse, die einzelnen Vorgang entsprechen, freigegeben werden. Dieser Wert sollte nicht mit EventName verwechselt werden.
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
            Ruft ab oder legt den Vorgangsnamen fest.
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
            Ruft ab oder legt sie fest &amp;Lt; Schlüssel, Wert&amp;Gt; Paare (normalerweise ein Wörterbuch&amp;Lt; String, String&amp;Gt;), die Details zum Ereignis enthält.
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
            Ruft ab oder legt der Ressourcengruppenname der betroffenen Ressource.
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
            Abrufen oder Festlegen der Ressourcen-Uri, der die Ressource eindeutig identifiziert wird, die dieses Ereignis verursacht hat.
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
            Ruft ab oder legt die ressourcenanbietername der betroffenen Ressource.
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
            Ruft ab oder legt den Ressourcentyp
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
            Ruft ab oder legt eine Zeichenfolge, die den Status des Vorgangs fest. Einige typische Werte sind: gestartet, ausgeführt wird, erfolgreich "," Fehler "und" aufgelöst.
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
            Ruft ab oder legt den Zeitstempel des fest, wenn das Ereignis für die Abfrage über diese API verfügbar war. Es ist im ISO 8601-Format. Dieser Wert darf nicht zu verwechseln EventTimestamp sein. Da es möglicherweise eine Verzögerung zwischen dem Zeitpunkt des Auftretens des Ereignisses und die Zeit, die das Ereignis an den Azure Protokollierungsinfrastruktur gesendet wird.
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
            Ruft ab oder legt dem Azure-Abonnement-Id in der Regel eine GUID.
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
            Ermittelt oder der Ereignisstatus Sub definiert. Die meisten der Zeit, wenn enthalten, zeichnet den HTTP-Statuscode des REST-Aufrufs. Häufig verwendete Werte sind: OK (HTTP-Statuscode: 200) erstelltes (HTTP-Statuscode: 201), akzeptiert (HTTP-Statuscode: 202), No Content (HTTP-Statuscode: 204), fehlerhafte Request(HTTP Status Code: 400), wurde Nichtgefunden (HTTP-Statuscode: 404), Konflikt (HTTP-Statuscode:: 409), interne Serverfehler (HTTP-Statuscode: 500), der Dienst ist nicht verfügbar (HTTP-Statuscode: 503), GatewayTimeout (HTTP-Statuscode: 504)
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
            Ruft ab oder legt den Azure-Mandanten-Id
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