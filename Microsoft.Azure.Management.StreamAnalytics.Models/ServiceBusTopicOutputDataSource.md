<Type Name="ServiceBusTopicOutputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource">
  <TypeSignature Language="C#" Value="public class ServiceBusTopicOutputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceBusTopicOutputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceBusTopicOutputDataSource&#xA;Inherits OutputDataSource" />
  <TypeSignature Language="F#" Value="type ServiceBusTopicOutputDataSource = class&#xA;    inherit OutputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.OutputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ServiceBus/Topic")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt eine Datenquelle für Service Bus-Thema Ausgabe an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusTopicOutputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ServiceBusTopicOutputDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceBusTopicOutputDataSource (string serviceBusNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string topicName = null, System.Collections.Generic.IList&lt;string&gt; propertyColumns = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string serviceBusNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string topicName, class System.Collections.Generic.IList`1&lt;string&gt; propertyColumns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional serviceBusNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional topicName As String = null, Optional propertyColumns As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource : string * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource (serviceBusNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, topicName, propertyColumns)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceBusNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="propertyColumns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceBusNamespace">Der Namespace, der die gewünschten Event Hub, Service Bus-Warteschlange, Service Bus-Thema usw. zugeordnet ist. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="sharedAccessPolicyName">Die SAS-Richtliniennamen für den Event Hub, Service Bus-Warteschlange, Service Bus-Thema usw. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="sharedAccessPolicyKey">Der SAS-Richtlinie-Schlüssel für die angegebene SAS-Richtlinie. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="topicName">Der Name des Service Bus-Thema. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="propertyColumns">Ein Zeichenfolgenarray mit den Namen der Ausgabespalten Service Bus-Nachrichten als benutzerdefinierte Eigenschaften zugeordnet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der ServiceBusTopicOutputDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; PropertyColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; PropertyColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.PropertyColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property PropertyColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PropertyColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.PropertyColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.propertyColumns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert ein Array der Namen von Ausgabespalten Service Bus-Nachrichten als benutzerdefinierte Eigenschaften zugeordnet werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceBusNamespace">
      <MemberSignature Language="C#" Value="public string ServiceBusNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceBusNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.ServiceBusNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceBusNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ServiceBusNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.ServiceBusNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceBusNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namespace, der die gewünschten Event Hub, Service Bus-Warteschlange, Service Bus-Thema usw. zugeordnet ist. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schlüssel des SAS-Richtlinie für die angegebene SAS-Richtlinie. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyName">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.SharedAccessPolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedAccessPolicyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des SAS-Richtlinie für den Event Hub, Service Bus-Warteschlange, Service Bus-Thema usw. fest. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopicName">
      <MemberSignature Language="C#" Value="public string TopicName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TopicName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.TopicName" />
      <MemberSignature Language="VB.NET" Value="Public Property TopicName As String" />
      <MemberSignature Language="F#" Value="member this.TopicName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.ServiceBusTopicOutputDataSource.TopicName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.topicName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Service Bus-Thema. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>