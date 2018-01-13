<Type Name="EventHubProperties" FullName="Microsoft.Azure.Management.IotHub.Models.EventHubProperties">
  <TypeSignature Language="C#" Value="public class EventHubProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EventHubProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.EventHubProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class EventHubProperties" />
  <TypeSignature Language="F#" Value="type EventHubProperties = class" />
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
            Die Eigenschaften des bereitgestellten Event Hub-kompatiblen Endpunkts vom IoT Hub verwendet wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EventHubProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EventHubProperties (Nullable&lt;long&gt; retentionTimeInDays = null, Nullable&lt;int&gt; partitionCount = null, System.Collections.Generic.IList&lt;string&gt; partitionIds = null, string path = null, string endpoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; retentionTimeInDays, valuetype System.Nullable`1&lt;int32&gt; partitionCount, class System.Collections.Generic.IList`1&lt;string&gt; partitionIds, string path, string endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional retentionTimeInDays As Nullable(Of Long) = null, Optional partitionCount As Nullable(Of Integer) = null, Optional partitionIds As IList(Of String) = null, Optional path As String = null, Optional endpoint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.EventHubProperties : Nullable&lt;int64&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.EventHubProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.EventHubProperties (retentionTimeInDays, partitionCount, partitionIds, path, endpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retentionTimeInDays" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="partitionIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="retentionTimeInDays">Die beibehaltungszeit für Gerät-zu-Cloud-Nachrichten in Tagen. Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#device-to-cloud-messages</param>
        <param name="partitionCount">Die Anzahl der Partitionen für Gerät-zu-Cloud-Nachrichten im Event Hub-kompatiblen Endpunkt empfangen. Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#device-to-cloud-messages.</param>
        <param name="partitionIds">Die Partitions-Ids in der Event Hub-kompatiblen Endpunkt.</param>
        <param name="path">Der Name des Ereignis-Hub-kompatibel.</param>
        <param name="endpoint">Der Event Hub-kompatiblen-Endpunkt.</param>
        <summary>
            Initialisiert eine neue Instanz der EventHubProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubProperties.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Event Hub-kompatiblen-Endpunkt ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubProperties.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Partitionen für Gerät-zu-Cloud-Nachrichten im Event Hub-kompatiblen Endpunkt empfangen. Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#device-to-cloud-messages.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PartitionIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PartitionIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.PartitionIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PartitionIds : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubProperties.PartitionIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="partitionIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Partitions-Ids in der Event Hub-kompatiblen Endpunkt ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubProperties.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Event Hub-kompatibel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTimeInDays">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; RetentionTimeInDays { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; RetentionTimeInDays" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.EventHubProperties.RetentionTimeInDays" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTimeInDays As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RetentionTimeInDays : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.EventHubProperties.RetentionTimeInDays" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTimeInDays")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die beibehaltungszeit für Gerät-zu-Cloud-Nachrichten in Tagen fest. Finden Sie unter: https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-messaging#device-to-cloud-messages
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>