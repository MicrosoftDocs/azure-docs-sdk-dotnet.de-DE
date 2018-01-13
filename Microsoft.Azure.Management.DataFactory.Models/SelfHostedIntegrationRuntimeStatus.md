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
            Common Language Runtime Integrationsstatus gehostet.
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
            Initialisiert eine neue Instanz der SelfHostedIntegrationRuntimeStatus-Klasse.
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
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="state">Der Status der integrationslaufzeit. Folgende Werte sind möglich: "Ursprünglichen", "Angehalten", "Gestartet", "starten", "Beenden", "needregistration" "", "Online", "Beschränkt", "Offline"</param>
        <param name="createTime">Der Zeitpunkt, zu dem der integrationslaufzeit erstellt wurde, im ISO8601-format.</param>
        <param name="taskQueueId">Die Task-Id der Warteschlange von der integrationslaufzeit.</param>
        <param name="internalChannelEncryption">Es wird verwendet, die festzulegende den Verschlüsselungsmodus für Kommunikationskanal zwischen Knoten (Wenn mehr als 2 Integration selbst gehosteten Common Language Runtime-Knoten vorhanden sind). Folgende Werte sind möglich: 'NotSet', 'SslEncrypted', 'NotEncrypted'</param>
        <param name="version">Version der Laufzeit der Integration.</param>
        <param name="nodes">Die Liste der Knoten für diese integrationslaufzeit.</param>
        <param name="scheduledUpdateDate">Das Datum, an dem der integrationslaufzeit geplant wird, um im ISO8601-Format zu aktualisieren.</param>
        <param name="updateDelayOffset">Die Zeit in das Datum, die vom Dienst zum Aktualisieren von der integrationslaufzeit geplant ist z. B. PT03H 3 Stunden</param>
        <param name="localTimeZoneOffset">Der lokalen Zeitzone in Stunden.</param>
        <param name="capabilities">Mit zusätzlichen Informationen über Integrationsfunktionen für die Common Language Runtime-Objekt.</param>
        <param name="serviceUrls">Die URLs für die Dienste, die im Integration Runtime Back-End-Dienst verwendet werden soll.</param>
        <param name="autoUpdate">Gibt an, ob automatische Aktualisierung der Common Language Runtime selbst gehosteten Integration aktiviert wurde. Folgende Werte sind möglich: "On", "deaktiviert"</param>
        <param name="versionStatus">Status der Integration Common Language Runtime-Version.</param>
        <summary>
            Initialisiert eine neue Instanz der SelfHostedIntegrationRuntimeStatus-Klasse.
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
            Ruft ab, ob die automatische Aktualisierung der Common Language Runtime selbst gehosteten Integration aktiviert wurde. Folgende Werte sind möglich: "On", "deaktiviert"
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
            Ruft-Objekt mit zusätzlichen Informationen über die Common Language Runtime-Integrationsfunktionen.
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
            Ruft den Zeitpunkt, zu dem der integrationslaufzeit im ISO8601-Format erstellt wurde.
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
            Ruft ab, die sie mit den Verschlüsselungsmodus für Kommunikationskanal zwischen Knoten festgelegt wird (Wenn mehr als 2 Integration selbst gehosteten Common Language Runtime-Knoten vorhanden sind). Folgende Werte sind möglich: 'NotSet', 'SslEncrypted', 'NotEncrypted'
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
            Ruft den Offset der Ortszeit Zone in Stunden ab.
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
            Ruft ab oder legt die Liste der Knoten für diese integrationslaufzeit fest.
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
            Ruft das Datum, an dem der integrationslaufzeit geplant wird, um im ISO8601-Format zu aktualisieren.
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
            Ruft die URLs für die Dienste, die im Integration Runtime Back-End-Dienst verwendet.
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
            Ruft die Task-Warteschlangen-Id von der integrationslaufzeit ab.
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
            Ruft die Zeit in das Datum, die vom Dienst zum Aktualisieren von der integrationslaufzeit, z. B. PT03H geplant beträgt 3 Stunden
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
            Ruft die Version von der integrationslaufzeit ab.
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
            Ruft die Laufzeitversion Integration Status ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>