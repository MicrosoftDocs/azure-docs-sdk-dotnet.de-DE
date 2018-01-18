<Type Name="IoTHubStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class IoTHubStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IoTHubStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class IoTHubStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type IoTHubStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Devices/IotHubs")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dd9c4-101">Beschreibt eine input IoT Hub-Datenquelle, die datenstromdaten enthält.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-101">Describes an IoT Hub input data source that contains stream data.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IoTHubStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dd9c4-102">Initialisiert eine neue Instanz der IoTHubStreamInputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-102">Initializes a new instance of the IoTHubStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IoTHubStreamInputDataSource (string iotHubNamespace = null, string sharedAccessPolicyName = null, string sharedAccessPolicyKey = null, string consumerGroupName = null, string endpoint = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string iotHubNamespace, string sharedAccessPolicyName, string sharedAccessPolicyKey, string consumerGroupName, string endpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional iotHubNamespace As String = null, Optional sharedAccessPolicyName As String = null, Optional sharedAccessPolicyKey As String = null, Optional consumerGroupName As String = null, Optional endpoint As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource : string * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource (iotHubNamespace, sharedAccessPolicyName, sharedAccessPolicyKey, consumerGroupName, endpoint)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="iotHubNamespace" Type="System.String" />
        <Parameter Name="sharedAccessPolicyName" Type="System.String" />
        <Parameter Name="sharedAccessPolicyKey" Type="System.String" />
        <Parameter Name="consumerGroupName" Type="System.String" />
        <Parameter Name="endpoint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="iotHubNamespace"><span data-ttu-id="dd9c4-103">Der Name oder der URI des IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-103">The name or the URI of the IoT Hub.</span></span>
            <span data-ttu-id="dd9c4-104">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-104">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyName"><span data-ttu-id="dd9c4-105">Die SAS-Richtliniennamen für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-105">The shared access policy name for the IoT Hub.</span></span> <span data-ttu-id="dd9c4-106">Diese Richtlinie muss mindestens den Dienst connect-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-106">This policy must contain at least the Service connect permission.</span></span> <span data-ttu-id="dd9c4-107">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-107">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="sharedAccessPolicyKey"><span data-ttu-id="dd9c4-108">Der SAS-Richtlinie-Schlüssel für die angegebene SAS-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-108">The shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="dd9c4-109">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-109">Required on PUT (CreateOrReplace) requests.</span></span></param>
        <param name="consumerGroupName"><span data-ttu-id="dd9c4-110">Der Name des ein IoT Hub-Consumergruppe, die zum Lesen von Ereignissen vom IoT Hub verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-110">The name of an IoT Hub Consumer Group that should be used to read events from the IoT Hub.</span></span> <span data-ttu-id="dd9c4-111">Wenn nicht angegeben, verwendet die Eingabe der Iot Hub-standardconsumergruppe.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-111">If not specified, the input uses the Iot Hub’s default consumer group.</span></span></param>
        <param name="endpoint"><span data-ttu-id="dd9c4-112">IoT Hub-Endpunkt für die Verbindung (d. h. "Nachrichten-Ereignisse, Meldungen/OperationsMonitoringEvents" usw..).</span><span class="sxs-lookup"><span data-stu-id="dd9c4-112">The IoT Hub endpoint to connect to (ie. messages/events, messages/operationsMonitoringEvents, etc.).</span></span></param>
        <summary>
            <span data-ttu-id="dd9c4-113">Initialisiert eine neue Instanz der IoTHubStreamInputDataSource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-113">Initializes a new instance of the IoTHubStreamInputDataSource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsumerGroupName">
      <MemberSignature Language="C#" Value="public string ConsumerGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConsumerGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.ConsumerGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property ConsumerGroupName As String" />
      <MemberSignature Language="F#" Value="member this.ConsumerGroupName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.ConsumerGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.consumerGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd9c4-114">Ruft ab oder legt den Namen des ein IoT Hub-Consumergruppe, die zum Lesen von Ereignissen vom IoT Hub verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-114">Gets or sets the name of an IoT Hub Consumer Group that should be used to read events from the IoT Hub.</span></span> <span data-ttu-id="dd9c4-115">Wenn nicht angegeben, verwendet die Eingabe der Iot Hub-standardconsumergruppe.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-115">If not specified, the input uses the Iot Hub’s default consumer group.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd9c4-116">Ruft ab oder legt den IoT Hub-Endpunkt für die Verbindung (d. h. "Nachrichten-Ereignisse, Meldungen/OperationsMonitoringEvents" usw..).</span><span class="sxs-lookup"><span data-stu-id="dd9c4-116">Gets or sets the IoT Hub endpoint to connect to (ie. messages/events, messages/operationsMonitoringEvents, etc.).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IotHubNamespace">
      <MemberSignature Language="C#" Value="public string IotHubNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IotHubNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.IotHubNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property IotHubNamespace As String" />
      <MemberSignature Language="F#" Value="member this.IotHubNamespace : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.IotHubNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.iotHubNamespace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dd9c4-117">Ruft ab oder legt den Namen oder den URI des IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-117">Gets or sets the name or the URI of the IoT Hub.</span></span> <span data-ttu-id="dd9c4-118">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-118">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyKey">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyKey : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyKey" />
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
            <span data-ttu-id="dd9c4-119">Ruft ab oder legt den Schlüssel des SAS-Richtlinie für die angegebene SAS-Richtlinie.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-119">Gets or sets the shared access policy key for the specified shared access policy.</span></span> <span data-ttu-id="dd9c4-120">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-120">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedAccessPolicyName">
      <MemberSignature Language="C#" Value="public string SharedAccessPolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedAccessPolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedAccessPolicyName As String" />
      <MemberSignature Language="F#" Value="member this.SharedAccessPolicyName : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.IoTHubStreamInputDataSource.SharedAccessPolicyName" />
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
            <span data-ttu-id="dd9c4-121">Ruft ab oder legt den Namen des SAS-Richtlinie für den IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-121">Gets or sets the shared access policy name for the IoT Hub.</span></span> <span data-ttu-id="dd9c4-122">Diese Richtlinie muss mindestens den Dienst connect-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-122">This policy must contain at least the Service connect permission.</span></span>
            <span data-ttu-id="dd9c4-123">Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dd9c4-123">Required on PUT (CreateOrReplace) requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>