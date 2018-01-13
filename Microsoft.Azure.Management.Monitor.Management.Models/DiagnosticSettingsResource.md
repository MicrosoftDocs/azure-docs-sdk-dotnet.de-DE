<Type Name="DiagnosticSettingsResource" FullName="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource">
  <TypeSignature Language="C#" Value="public class DiagnosticSettingsResource : Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiagnosticSettingsResource extends Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" />
  <TypeSignature Language="VB.NET" Value="Public Class DiagnosticSettingsResource&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type DiagnosticSettingsResource = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Monitor.Management.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die diagnoseeinstellung-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.#ctor" />
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
            Initialisiert eine neue Instanz der DiagnosticSettingsResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiagnosticSettingsResource (string id = null, string name = null, string type = null, string storageAccountId = null, string eventHubAuthorizationRuleId = null, string eventHubName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; metrics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; logs = null, string workspaceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string storageAccountId, string eventHubAuthorizationRuleId, string eventHubName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; metrics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; logs, string workspaceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings},System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Management.Models.LogSettings},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional storageAccountId As String = null, Optional eventHubAuthorizationRuleId As String = null, Optional eventHubName As String = null, Optional metrics As IList(Of MetricSettings) = null, Optional logs As IList(Of LogSettings) = null, Optional workspaceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource : string * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; * string -&gt; Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource (id, name, type, storageAccountId, eventHubAuthorizationRuleId, eventHubName, metrics, logs, workspaceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="eventHubAuthorizationRuleId" Type="System.String" />
        <Parameter Name="eventHubName" Type="System.String" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt;" />
        <Parameter Name="logs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt;" />
        <Parameter Name="workspaceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Azure-Ressourcen-Id</param>
        <param name="name">Name des Azure-Ressource</param>
        <param name="type">Azure-Ressourcentyp</param>
        <param name="storageAccountId">Die Ressourcen-ID des Speicherkontos an, das Sie zum Senden von Diagnoseprotokollen möchten.</param>
        <param name="eventHubAuthorizationRuleId">Die Ressourcen-Id für die Event Hub-Autorisierungsregel.</param>
        <param name="eventHubName">Der Name des Event Hubs. Wenn keine Angabe erfolgt, wird der standardmäßige Event Hub ausgewählt werden.</param>
        <param name="metrics">die Liste der metrikeinstellungen.</param>
        <param name="logs">die Liste der protokolleinstellungen.</param>
        <param name="workspaceId">Die Arbeitsbereichs-ID (Ressourcen-ID eines Protokollanalyse-Arbeitsbereichs) für einen Arbeitsbereich für Protokollanalyse, den Sie zum Senden von Diagnoseprotokollen möchten. Beispiel: /subscriptions/4b9e8510-67ab-4e9a-95a9-e2f1e570ea9c/resourceGroups/insights-integration/providers/Microsoft.OperationalInsights/workspaces/viruela2</param>
        <summary>
            Initialisiert eine neue Instanz der DiagnosticSettingsResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAuthorizationRuleId">
      <MemberSignature Language="C#" Value="public string EventHubAuthorizationRuleId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubAuthorizationRuleId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.EventHubAuthorizationRuleId" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubAuthorizationRuleId As String" />
      <MemberSignature Language="F#" Value="member this.EventHubAuthorizationRuleId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.EventHubAuthorizationRuleId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventHubAuthorizationRuleId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressourcen-Id für die Event Hub-Autorisierungsregel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubName">
      <MemberSignature Language="C#" Value="public string EventHubName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventHubName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.EventHubName" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubName As String" />
      <MemberSignature Language="F#" Value="member this.EventHubName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.EventHubName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventHubName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Event Hubs. Wenn keine Angabe erfolgt, wird der standardmäßige Event Hub ausgewählt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Logs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; Logs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; Logs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.Logs" />
      <MemberSignature Language="VB.NET" Value="Public Property Logs As IList(Of LogSettings)" />
      <MemberSignature Language="F#" Value="member this.Logs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.Logs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.logs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.LogSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste von protokolleinstellungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; Metrics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public Property Metrics As IList(Of MetricSettings)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.Metrics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metrics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Management.Models.MetricSettings&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der metrikeinstellungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressourcen-ID des Speicherkontos an, das Sie zum Senden von Diagnoseprotokollen möchten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkspaceId">
      <MemberSignature Language="C#" Value="public string WorkspaceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkspaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.WorkspaceId" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkspaceId As String" />
      <MemberSignature Language="F#" Value="member this.WorkspaceId : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.DiagnosticSettingsResource.WorkspaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workspaceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Arbeitsbereichs-ID (Ressourcen-ID eines Protokollanalyse-Arbeitsbereichs) für einen Arbeitsbereich für Protokollanalyse, den Sie zum Senden von Diagnoseprotokollen möchten. Beispiel: /subscriptions/4b9e8510-67ab-4e9a-95a9-e2f1e570ea9c/resourceGroups/insights-integration/providers/Microsoft.OperationalInsights/workspaces/viruela2
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>