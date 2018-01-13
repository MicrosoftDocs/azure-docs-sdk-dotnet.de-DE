<Type Name="IotHubProperties" FullName="Microsoft.Azure.Management.IotHub.Models.IotHubProperties">
  <TypeSignature Language="C#" Value="public class IotHubProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IotHubProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.IotHubProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class IotHubProperties" />
  <TypeSignature Language="F#" Value="type IotHubProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften eines IoT Hubs.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IotHubProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IotHubProperties (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; authorizationPolicies = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; ipFilterRules = null, string provisioningState = null, string hostName = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; eventHubEndpoints = null, Microsoft.Azure.Management.IotHub.Models.RoutingProperties routing = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; storageEndpoints = null, System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; messagingEndpoints = null, Nullable&lt;bool&gt; enableFileUploadNotifications = null, Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties cloudToDevice = null, string comments = null, Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties operationsMonitoringProperties = null, string features = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; authorizationPolicies, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; ipFilterRules, string provisioningState, string hostName, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; eventHubEndpoints, class Microsoft.Azure.Management.IotHub.Models.RoutingProperties routing, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; storageEndpoints, class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; messagingEndpoints, valuetype System.Nullable`1&lt;bool&gt; enableFileUploadNotifications, class Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties cloudToDevice, string comments, class Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties operationsMonitoringProperties, string features) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.IpFilterRule},System.String,System.String,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.IotHub.Models.EventHubProperties},Microsoft.Azure.Management.IotHub.Models.RoutingProperties,System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties},System.Collections.Generic.IDictionary{System.String,Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties},System.Nullable{System.Boolean},Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties,System.String,Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.IotHubProperties : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; * Microsoft.Azure.Management.IotHub.Models.RoutingProperties * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; * System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties * string * Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties * string -&gt; Microsoft.Azure.Management.IotHub.Models.IotHubProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.IotHubProperties (authorizationPolicies, ipFilterRules, provisioningState, hostName, eventHubEndpoints, routing, storageEndpoints, messagingEndpoints, enableFileUploadNotifications, cloudToDevice, comments, operationsMonitoringProperties, features)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authorizationPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;" />
        <Parameter Name="ipFilterRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="eventHubEndpoints" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt;" />
        <Parameter Name="routing" Type="Microsoft.Azure.Management.IotHub.Models.RoutingProperties" />
        <Parameter Name="storageEndpoints" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt;" />
        <Parameter Name="messagingEndpoints" Type="System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt;" />
        <Parameter Name="enableFileUploadNotifications" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cloudToDevice" Type="Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties" />
        <Parameter Name="comments" Type="System.String" />
        <Parameter Name="operationsMonitoringProperties" Type="Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties" />
        <Parameter Name="features" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationPolicies">Die SAS-Richtlinien, die Sie verwenden können, um eine Verbindung mit dem IoT Hub zu sichern.</param>
        <param name="ipFilterRules">Die IP-Filter-Regeln.</param>
        <param name="provisioningState">Der Bereitstellungsstatus.</param>
        <param name="hostName">Der Name des Hosts.</param>
        <param name="eventHubEndpoints">Die Eigenschaften für den Event Hub-kompatiblen-Endpunkt. Die möglichen Schlüssel, um dieses Wörterbuch werden Ereignisse und OperationsMonitoringEvents. Beide dieser Schlüssel müssen im Wörterbuch beim Erstellen oder aktualisieren Aufrufe für den IoT Hub erstellen vorhanden sein.</param>
        <param name="routing">To be added.</param>
        <param name="storageEndpoints">Die Liste der Azure-Speicher-Endpunkte, in dem Sie Dateien hochladen können. Sie können derzeit nur ein Azure Storage-Konto konfigurieren, und benötigen, die die Schlüssel als $default.
            Mehr als ein Speicherkonto angeben, tritt ein Fehler ausgelöst wird. Einen Wert für diese Eigenschaft angeben nicht, wenn die EnableFileUploadNotifications-Eigenschaft auf "true" wird einen Fehler ausgelöst wird, festgelegt ist.</param>
        <param name="messagingEndpoints">Der Endpunkt-Nachrichteneigenschaften für die Datei hochladen Benachrichtigungswarteschlange.</param>
        <param name="enableFileUploadNotifications">Wenn "true", Datei hochladen Benachrichtigungen aktiviert sind.</param>
        <param name="cloudToDevice">To be added.</param>
        <param name="comments">IoT Hub-Kommentare.</param>
        <param name="operationsMonitoringProperties">To be added.</param>
        <param name="features">Features und Funktionen, die für den IoT Hub aktiviert. Folgende Werte sind möglich: 'None', 'DeviceManagement'</param>
        <summary>
            Initialisiert eine neue Instanz der IotHubProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthorizationPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; AuthorizationPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; AuthorizationPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.AuthorizationPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthorizationPolicies As IList(Of SharedAccessSignatureAuthorizationRule)" />
      <MemberSignature Language="F#" Value="member this.AuthorizationPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.AuthorizationPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authorizationPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.SharedAccessSignatureAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der SAS-Richtlinien, die Sie verwenden können, um eine Verbindung mit dem IoT Hub zu sichern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudToDevice">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties CloudToDevice { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties CloudToDevice" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.CloudToDevice" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudToDevice As CloudToDeviceProperties" />
      <MemberSignature Language="F#" Value="member this.CloudToDevice : Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.CloudToDevice" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudToDevice")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.CloudToDeviceProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Comments">
      <MemberSignature Language="C#" Value="public string Comments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Comments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Comments" />
      <MemberSignature Language="VB.NET" Value="Public Property Comments As String" />
      <MemberSignature Language="F#" Value="member this.Comments : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Comments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="comments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt IoT Hub-Kommentare.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableFileUploadNotifications">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableFileUploadNotifications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableFileUploadNotifications" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.EnableFileUploadNotifications" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableFileUploadNotifications As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableFileUploadNotifications : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.EnableFileUploadNotifications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableFileUploadNotifications")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, wenn "true", Datei hochladen Benachrichtigungen aktiviert sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; EventHubEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; EventHubEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.EventHubEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubEndpoints As IDictionary(Of String, EventHubProperties)" />
      <MemberSignature Language="F#" Value="member this.EventHubEndpoints : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.EventHubEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventHubEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.EventHubProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Event Hub-kompatiblen Endpunkteigenschaften. Die möglichen Schlüssel, um dieses Wörterbuch werden Ereignisse und OperationsMonitoringEvents. Beide dieser Schlüssel müssen im Wörterbuch beim Erstellen oder aktualisieren Aufrufe für den IoT Hub erstellen vorhanden sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Features">
      <MemberSignature Language="C#" Value="public string Features { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Features" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Features" />
      <MemberSignature Language="VB.NET" Value="Public Property Features As String" />
      <MemberSignature Language="F#" Value="member this.Features : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Features" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="features")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, die Features und Funktionen, die für den IoT Hub aktiviert.
            Folgende Werte sind möglich: 'None', 'DeviceManagement'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Hosts ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpFilterRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; IpFilterRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; IpFilterRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.IpFilterRules" />
      <MemberSignature Language="VB.NET" Value="Public Property IpFilterRules As IList(Of IpFilterRule)" />
      <MemberSignature Language="F#" Value="member this.IpFilterRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.IpFilterRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipFilterRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.IpFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Filter-Regeln.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MessagingEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; MessagingEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; MessagingEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.MessagingEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property MessagingEndpoints As IDictionary(Of String, MessagingEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.MessagingEndpoints : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.MessagingEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="messagingEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.MessagingEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Nachrichteneigenschaften-Endpunkt für die Benachrichtigungswarteschlange für Datei hochladen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationsMonitoringProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties OperationsMonitoringProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties OperationsMonitoringProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.OperationsMonitoringProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationsMonitoringProperties As OperationsMonitoringProperties" />
      <MemberSignature Language="F#" Value="member this.OperationsMonitoringProperties : Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.OperationsMonitoringProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operationsMonitoringProperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.OperationsMonitoringProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bereitstellungsstatus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routing">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.IotHub.Models.RoutingProperties Routing { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.IotHub.Models.RoutingProperties Routing" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Routing" />
      <MemberSignature Language="VB.NET" Value="Public Property Routing As RoutingProperties" />
      <MemberSignature Language="F#" Value="member this.Routing : Microsoft.Azure.Management.IotHub.Models.RoutingProperties with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Routing" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.IotHub.Models.RoutingProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; StorageEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, class Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; StorageEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.StorageEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageEndpoints As IDictionary(Of String, StorageEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.StorageEndpoints : System.Collections.Generic.IDictionary&lt;string, Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.IotHubProperties.StorageEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,Microsoft.Azure.Management.IotHub.Models.StorageEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Endpunkte der Azure-Speicher, in dem Sie Dateien hochladen. Sie können derzeit nur ein Azure Storage-Konto konfigurieren, und benötigen, die die Schlüssel als $default. Mehr als ein Speicherkonto angeben, tritt ein Fehler ausgelöst wird. Einen Wert für diese Eigenschaft angeben nicht, wenn die EnableFileUploadNotifications-Eigenschaft auf "true" wird einen Fehler ausgelöst wird, festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.IotHubProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="iotHubProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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