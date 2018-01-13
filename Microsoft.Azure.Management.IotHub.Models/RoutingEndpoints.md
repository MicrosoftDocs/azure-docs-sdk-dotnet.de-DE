<Type Name="RoutingEndpoints" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints">
  <TypeSignature Language="C#" Value="public class RoutingEndpoints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingEndpoints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingEndpoints" />
  <TypeSignature Language="F#" Value="type RoutingEndpoints = class" />
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
            Die Eigenschaften im Zusammenhang mit der benutzerdefinierte Endpunkte, die an die Ihren IoT Hub Nachrichten basierend auf die Senderegeln weiterleitet. Maximal 10 benutzerdefinierte Endpunkte für alle Endpoint-Typen für kostenpflichtige Hubs zulässig sind und nur 1 benutzerdefinierter Endpunkt zulässig ist für alle Endpoint-Typen für kostenlose Hubs.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEndpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RoutingEndpoints-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingEndpoints (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; serviceBusQueues = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; serviceBusTopics = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; eventHubs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; storageContainers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; serviceBusQueues, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; serviceBusTopics, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; eventHubs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; storageContainers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties},System.Collections.Generic.IList{Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusQueues As IList(Of RoutingServiceBusQueueEndpointProperties) = null, Optional serviceBusTopics As IList(Of RoutingServiceBusTopicEndpointProperties) = null, Optional eventHubs As IList(Of RoutingEventHubProperties) = null, Optional storageContainers As IList(Of RoutingStorageContainerProperties) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints (serviceBusQueues, serviceBusTopics, eventHubs, storageContainers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusQueues" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt;" />
        <Parameter Name="serviceBusTopics" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt;" />
        <Parameter Name="eventHubs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt;" />
        <Parameter Name="storageContainers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceBusQueues">Die Liste der Service Bus-Warteschlange Endpunkte, die von IoT Hub die Nachrichten, weitergeleitet, basierend auf die Senderegeln.</param>
        <param name="serviceBusTopics">Die Liste der Service Bus-Thema-Endpunkte, die IoT Hub der Nachrichten, die Senderegeln Grundlage weiterleitet.</param>
        <param name="eventHubs">Die Liste der Endpunkte IoT Hub Nachrichten, weiterleitet, basierend auf die Senderegeln Event Hubs. Diese Liste enthält keine integrierte Event Hubs-Endpunkt.</param>
        <param name="storageContainers">Die Liste der Speicher-containerendpunkten, IoT Hub Nachrichten, weitergeleitet, basierend auf die Senderegeln.</param>
        <summary>
            Initialisiert eine neue Instanz der RoutingEndpoints-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; EventHubs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; EventHubs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.EventHubs" />
      <MemberSignature Language="VB.NET" Value="Public Property EventHubs As IList(Of RoutingEventHubProperties)" />
      <MemberSignature Language="F#" Value="member this.EventHubs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.EventHubs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eventHubs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingEventHubProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Liste der Endpunkte des Event Hubs, IoT Hub Nachrichten, basierend auf die Senderegeln weiterleitet. Diese Liste enthält keine integrierte Event Hubs-Endpunkt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusQueues">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; ServiceBusQueues { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; ServiceBusQueues" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusQueues" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusQueues As IList(Of RoutingServiceBusQueueEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.ServiceBusQueues : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusQueues" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceBusQueues")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusQueueEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Liste der Endpunkte für Service Bus-Warteschlange, die von IoT Hub die Nachrichten an, basierend auf die Senderegeln weitergeleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusTopics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; ServiceBusTopics { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; ServiceBusTopics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusTopics" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusTopics As IList(Of RoutingServiceBusTopicEndpointProperties)" />
      <MemberSignature Language="F#" Value="member this.ServiceBusTopics : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.ServiceBusTopics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="serviceBusTopics")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Endpunkte der Service Bus-Thema, die der IoT Hub die Nachrichten an, basierend auf die Senderegeln weiterleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; StorageContainers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; StorageContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.StorageContainers" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageContainers As IList(Of RoutingStorageContainerProperties)" />
      <MemberSignature Language="F#" Value="member this.StorageContainers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingEndpoints.StorageContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageContainers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Liste der Container speicherendpunkte, IoT Hub Nachrichten, basierend auf die Senderegeln weiterleitet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>