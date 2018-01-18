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
            <span data-ttu-id="933c9-101">Die Eigenschaften eines IoT Hubs.</span><span class="sxs-lookup"><span data-stu-id="933c9-101">The properties of an IoT hub.</span></span>
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
            <span data-ttu-id="933c9-102">Initialisiert eine neue Instanz der IotHubProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="933c9-102">Initializes a new instance of the IotHubProperties class.</span></span>
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
        <param name="authorizationPolicies"><span data-ttu-id="933c9-103">Die SAS-Richtlinien, die Sie verwenden können, um eine Verbindung mit dem IoT Hub zu sichern.</span><span class="sxs-lookup"><span data-stu-id="933c9-103">The shared access policies you can use to secure a connection to the IoT hub.</span></span></param>
        <param name="ipFilterRules"><span data-ttu-id="933c9-104">Die IP-Filter-Regeln.</span><span class="sxs-lookup"><span data-stu-id="933c9-104">The IP filter rules.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="933c9-105">Der Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="933c9-105">The provisioning state.</span></span></param>
        <param name="hostName"><span data-ttu-id="933c9-106">Der Name des Hosts.</span><span class="sxs-lookup"><span data-stu-id="933c9-106">The name of the host.</span></span></param>
        <param name="eventHubEndpoints"><span data-ttu-id="933c9-107">Die Eigenschaften für den Event Hub-kompatiblen-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="933c9-107">The Event Hub-compatible endpoint properties.</span></span> <span data-ttu-id="933c9-108">Die möglichen Schlüssel, um dieses Wörterbuch werden Ereignisse und OperationsMonitoringEvents.</span><span class="sxs-lookup"><span data-stu-id="933c9-108">The possible keys to this dictionary are events and operationsMonitoringEvents.</span></span> <span data-ttu-id="933c9-109">Beide dieser Schlüssel müssen im Wörterbuch beim Erstellen oder aktualisieren Aufrufe für den IoT Hub erstellen vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="933c9-109">Both of these keys have to be present in the dictionary while making create or update calls for the IoT hub.</span></span></param>
        <param name="routing">To be added.</param>
        <param name="storageEndpoints"><span data-ttu-id="933c9-110">Die Liste der Azure-Speicher-Endpunkte, in dem Sie Dateien hochladen können.</span><span class="sxs-lookup"><span data-stu-id="933c9-110">The list of Azure Storage endpoints where you can upload files.</span></span> <span data-ttu-id="933c9-111">Sie können derzeit nur ein Azure Storage-Konto konfigurieren, und benötigen, die die Schlüssel als $default.</span><span class="sxs-lookup"><span data-stu-id="933c9-111">Currently you can configure only one Azure Storage account and that MUST have its key as $default.</span></span>
            <span data-ttu-id="933c9-112">Mehr als ein Speicherkonto angeben, tritt ein Fehler ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="933c9-112">Specifying more than one storage account causes an error to be thrown.</span></span> <span data-ttu-id="933c9-113">Einen Wert für diese Eigenschaft angeben nicht, wenn die EnableFileUploadNotifications-Eigenschaft auf "true" wird einen Fehler ausgelöst wird, festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="933c9-113">Not specifying a value for this property when the enableFileUploadNotifications property is set to True, causes an error to be thrown.</span></span></param>
        <param name="messagingEndpoints"><span data-ttu-id="933c9-114">Der Endpunkt-Nachrichteneigenschaften für die Datei hochladen Benachrichtigungswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="933c9-114">The messaging endpoint properties for the file upload notification queue.</span></span></param>
        <param name="enableFileUploadNotifications"><span data-ttu-id="933c9-115">Wenn "true", Datei hochladen Benachrichtigungen aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="933c9-115">If True, file upload notifications are enabled.</span></span></param>
        <param name="cloudToDevice">To be added.</param>
        <param name="comments"><span data-ttu-id="933c9-116">IoT Hub-Kommentare.</span><span class="sxs-lookup"><span data-stu-id="933c9-116">IoT hub comments.</span></span></param>
        <param name="operationsMonitoringProperties">To be added.</param>
        <param name="features"><span data-ttu-id="933c9-117">Features und Funktionen, die für den IoT Hub aktiviert.</span><span class="sxs-lookup"><span data-stu-id="933c9-117">The capabilities and features enabled for the IoT hub.</span></span> <span data-ttu-id="933c9-118">Folgende Werte sind möglich: 'None', 'DeviceManagement'</span><span class="sxs-lookup"><span data-stu-id="933c9-118">Possible values include: 'None', 'DeviceManagement'</span></span></param>
        <summary>
            <span data-ttu-id="933c9-119">Initialisiert eine neue Instanz der IotHubProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="933c9-119">Initializes a new instance of the IotHubProperties class.</span></span>
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
            <span data-ttu-id="933c9-120">Abrufen oder Festlegen der SAS-Richtlinien, die Sie verwenden können, um eine Verbindung mit dem IoT Hub zu sichern.</span><span class="sxs-lookup"><span data-stu-id="933c9-120">Gets or sets the shared access policies you can use to secure a connection to the IoT hub.</span></span>
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
            <span data-ttu-id="933c9-121">Ruft ab oder legt IoT Hub-Kommentare.</span><span class="sxs-lookup"><span data-stu-id="933c9-121">Gets or sets ioT hub comments.</span></span>
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
            <span data-ttu-id="933c9-122">Ruft ab oder legt fest, wenn "true", Datei hochladen Benachrichtigungen aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="933c9-122">Gets or sets if True, file upload notifications are enabled.</span></span>
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
            <span data-ttu-id="933c9-123">Abrufen oder Festlegen der Event Hub-kompatiblen Endpunkteigenschaften.</span><span class="sxs-lookup"><span data-stu-id="933c9-123">Gets or sets the Event Hub-compatible endpoint properties.</span></span> <span data-ttu-id="933c9-124">Die möglichen Schlüssel, um dieses Wörterbuch werden Ereignisse und OperationsMonitoringEvents.</span><span class="sxs-lookup"><span data-stu-id="933c9-124">The possible keys to this dictionary are events and operationsMonitoringEvents.</span></span> <span data-ttu-id="933c9-125">Beide dieser Schlüssel müssen im Wörterbuch beim Erstellen oder aktualisieren Aufrufe für den IoT Hub erstellen vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="933c9-125">Both of these keys have to be present in the dictionary while making create or update calls for the IoT hub.</span></span>
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
            <span data-ttu-id="933c9-126">Ruft ab, oder legt sie fest, die Features und Funktionen, die für den IoT Hub aktiviert.</span><span class="sxs-lookup"><span data-stu-id="933c9-126">Gets or sets the capabilities and features enabled for the IoT hub.</span></span>
            <span data-ttu-id="933c9-127">Folgende Werte sind möglich: 'None', 'DeviceManagement'</span><span class="sxs-lookup"><span data-stu-id="933c9-127">Possible values include: 'None', 'DeviceManagement'</span></span>
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
            <span data-ttu-id="933c9-128">Ruft den Namen des Hosts ab.</span><span class="sxs-lookup"><span data-stu-id="933c9-128">Gets the name of the host.</span></span>
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
            <span data-ttu-id="933c9-129">Ruft ab oder legt die IP-Filter-Regeln.</span><span class="sxs-lookup"><span data-stu-id="933c9-129">Gets or sets the IP filter rules.</span></span>
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
            <span data-ttu-id="933c9-130">Abrufen oder Festlegen der Nachrichteneigenschaften-Endpunkt für die Benachrichtigungswarteschlange für Datei hochladen.</span><span class="sxs-lookup"><span data-stu-id="933c9-130">Gets or sets the messaging endpoint properties for the file upload notification queue.</span></span>
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
            <span data-ttu-id="933c9-131">Ruft den Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="933c9-131">Gets the provisioning state.</span></span>
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
            <span data-ttu-id="933c9-132">Ruft ab oder legt die Liste der Endpunkte der Azure-Speicher, in dem Sie Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="933c9-132">Gets or sets the list of Azure Storage endpoints where you can upload files.</span></span> <span data-ttu-id="933c9-133">Sie können derzeit nur ein Azure Storage-Konto konfigurieren, und benötigen, die die Schlüssel als $default.</span><span class="sxs-lookup"><span data-stu-id="933c9-133">Currently you can configure only one Azure Storage account and that MUST have its key as $default.</span></span> <span data-ttu-id="933c9-134">Mehr als ein Speicherkonto angeben, tritt ein Fehler ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="933c9-134">Specifying more than one storage account causes an error to be thrown.</span></span> <span data-ttu-id="933c9-135">Einen Wert für diese Eigenschaft angeben nicht, wenn die EnableFileUploadNotifications-Eigenschaft auf "true" wird einen Fehler ausgelöst wird, festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="933c9-135">Not specifying a value for this property when the enableFileUploadNotifications property is set to True, causes an error to be thrown.</span></span>
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
            <span data-ttu-id="933c9-136">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="933c9-136">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="933c9-137">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="933c9-137">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>