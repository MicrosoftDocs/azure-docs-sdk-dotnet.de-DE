<Type Name="NamespaceCreateOrUpdateParameters" FullName="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters">
  <TypeSignature Language="C#" Value="public class NamespaceCreateOrUpdateParameters : Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NamespaceCreateOrUpdateParameters extends Microsoft.Azure.Management.NotificationHubs.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class NamespaceCreateOrUpdateParameters&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NamespaceCreateOrUpdateParameters = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.NotificationHubs.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Die Parameter des Vorgangs CreateOrUpdate Namespace angegeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceCreateOrUpdateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der NamespaceCreateOrUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NamespaceCreateOrUpdateParameters (string location, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.NotificationHubs.Models.Sku sku = null, string namespaceCreateOrUpdateParametersName = null, string provisioningState = null, string region = null, string status = null, Nullable&lt;DateTime&gt; createdAt = null, string serviceBusEndpoint = null, string subscriptionId = null, string scaleUnit = null, Nullable&lt;bool&gt; enabled = null, Nullable&lt;bool&gt; critical = null, Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.NotificationHubs.Models.Sku sku, string namespaceCreateOrUpdateParametersName, string provisioningState, string region, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdAt, string serviceBusEndpoint, string subscriptionId, string scaleUnit, valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;bool&gt; critical, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; namespaceType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.NotificationHubs.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.NotificationHubs.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; -&gt; Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters" Usage="new Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters (location, id, name, type, tags, sku, namespaceCreateOrUpdateParametersName, provisioningState, region, status, createdAt, serviceBusEndpoint, subscriptionId, scaleUnit, enabled, critical, namespaceType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.NotificationHubs.Models.Sku" />
        <Parameter Name="namespaceCreateOrUpdateParametersName" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="createdAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="serviceBusEndpoint" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="scaleUnit" Type="System.String" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="critical" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="namespaceType" Type="System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;" />
      </Parameters>
      <Docs>
        <param name="location">Speicherort von Ressourcen</param>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="tags">Ressourcentags</param>
        <param name="sku">Die Sku des erstellten namespace</param>
        <param name="namespaceCreateOrUpdateParametersName">Der Name des Namespaces.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der der Namespace.</param>
        <param name="region">Gibt die Zielregion an, in der der Namespace erstellt werden soll. Es kann eine der folgenden Werte: Australien EastAustralia SoutheastCentral USEast USEast USA 2West USNorth zentralen USSouth USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest Mitteleuropa</param>
        <param name="status">Status des Namespaces. Es kann eine der folgenden Werte: 1 = Created/Active2 = Creating3 = Suspended4 = wird gelöscht</param>
        <param name="createdAt">Der Zeitpunkt, zu der Namespace erstellt wurde.</param>
        <param name="serviceBusEndpoint">Der Endpunkt, den Sie verwenden können, um NotificationHub-Vorgänge auszuführen.</param>
        <param name="subscriptionId">Die Id des Azure-Abonnements den Namespace zugeordnet werden soll.</param>
        <param name="scaleUnit">Skalierungseinheit hat, in dem der Namespace erstellt wird</param>
        <param name="enabled">Und zwar unabhängig davon, ob der Namespace derzeit aktiviert ist.</param>
        <param name="critical">Der Namespace, und zwar unabhängig davon, ob als "Kritisch" festgelegt ist.</param>
        <param name="namespaceType">Der Namespace-Typ. Folgende Werte sind möglich: 'Messaging', 'NotificationHub'</param>
        <summary>
            Initialisiert eine neue Instanz der NamespaceCreateOrUpdateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.CreatedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.CreatedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt der Erstellung der Namespace.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Critical">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Critical { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Critical" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Critical" />
      <MemberSignature Language="VB.NET" Value="Public Property Critical As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Critical : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Critical" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.critical")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, und zwar unabhängig davon, ob der Namespace als "Kritisch" festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, und zwar unabhängig davon, ob der Namespace derzeit aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceCreateOrUpdateParametersName">
      <MemberSignature Language="C#" Value="public string NamespaceCreateOrUpdateParametersName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamespaceCreateOrUpdateParametersName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceCreateOrUpdateParametersName" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceCreateOrUpdateParametersName As String" />
      <MemberSignature Language="F#" Value="member this.NamespaceCreateOrUpdateParametersName : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceCreateOrUpdateParametersName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Namespaces fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NamespaceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; NamespaceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceType" />
      <MemberSignature Language="VB.NET" Value="Public Property NamespaceType As Nullable(Of NamespaceType)" />
      <MemberSignature Language="F#" Value="member this.NamespaceType : Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt; with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.NamespaceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.namespaceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.NotificationHubs.Models.NamespaceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namespace-Typ fest. Folgende Werte sind möglich: 'Messaging', 'NotificationHub'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, der den Namespace der Bereitstellungsstatus.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.region")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Zielregion an, in dem der Namespace erstellt werden soll. Es kann eine der folgenden Werte: Australien EastAustralia SoutheastCentral USEast USEast USA 2West USNorth zentralen USSouth USEast AsiaSoutheast AsiaBrazil SouthJapan EastJapan WestNorth EuropeWest Mitteleuropa
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleUnit">
      <MemberSignature Language="C#" Value="public string ScaleUnit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScaleUnit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ScaleUnit" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleUnit As String" />
      <MemberSignature Language="F#" Value="member this.ScaleUnit : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ScaleUnit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleUnit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Skalierungseinheit hat, ruft der Namespace erstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusEndpoint">
      <MemberSignature Language="C#" Value="public string ServiceBusEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ServiceBusEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusEndpoint : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.ServiceBusEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Endpunkt, den Sie verwenden können, um NotificationHub-Vorgänge auszuführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Status des Namespaces. Es kann eine der folgenden Werte: 1 = Created/Active2 = Creating3 = Suspended4 = wird gelöscht
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.NotificationHubs.Models.NamespaceCreateOrUpdateParameters.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Id des Azure-Abonnements den Namespace zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>