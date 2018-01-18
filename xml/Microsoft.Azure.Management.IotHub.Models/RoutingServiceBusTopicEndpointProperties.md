<Type Name="RoutingServiceBusTopicEndpointProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties">
  <TypeSignature Language="C#" Value="public class RoutingServiceBusTopicEndpointProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingServiceBusTopicEndpointProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingServiceBusTopicEndpointProperties" />
  <TypeSignature Language="F#" Value="type RoutingServiceBusTopicEndpointProperties = class" />
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
            <span data-ttu-id="a6c6c-101">Die Eigenschaften im Zusammenhang mit Endpunkttypen der Servicebus-Thema.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-101">The properties related to service bus topic endpoint types.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingServiceBusTopicEndpointProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a6c6c-102">Initialisiert eine neue Instanz der RoutingServiceBusTopicEndpointProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-102">Initializes a new instance of the RoutingServiceBusTopicEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingServiceBusTopicEndpointProperties (string connectionString, string name, string subscriptionId = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string name, string subscriptionId, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, name As String, Optional subscriptionId As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties : string * string * string * string -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties (connectionString, name, subscriptionId, resourceGroup)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"><span data-ttu-id="a6c6c-103">Die Verbindungszeichenfolge der Servicebus-Thema-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-103">The connection string of the service bus topic endpoint.</span></span></param>
        <param name="name"><span data-ttu-id="a6c6c-104">Der Name zum Identifizieren von diesem Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-104">The name that identifies this endpoint.</span></span> <span data-ttu-id="a6c6c-105">Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-105">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="a6c6c-106">Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-106">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="a6c6c-107">Endpunktnamen müssen über Endpunkttypen eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-107">Endpoint names must be unique across endpoint types.</span></span>  <span data-ttu-id="a6c6c-108">Der Name muss nicht identisch mit dem tatsächlichen Themanamen sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-108">The name need not be the same as the actual topic name.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="a6c6c-109">Die Abonnement-ID des Servicebus-Thema-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-109">The subscription identifier of the service bus topic endpoint.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="a6c6c-110">Der Name der Ressourcengruppe des Servicebus-Thema-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-110">The name of the resource group of the service bus topic endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="a6c6c-111">Initialisiert eine neue Instanz der RoutingServiceBusTopicEndpointProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-111">Initializes a new instance of the RoutingServiceBusTopicEndpointProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6c6c-112">Ruft ab oder legt die Verbindungszeichenfolge der Servicebus-Thema-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-112">Gets or sets the connection string of the service bus topic endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6c6c-113">Ruft ab oder legt den Namen, der diesen Endpunkt identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-113">Gets or sets the name that identifies this endpoint.</span></span> <span data-ttu-id="a6c6c-114">Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-114">The name can only include alphanumeric characters, periods, underscores, hyphens and has a maximum length of 64 characters.</span></span> <span data-ttu-id="a6c6c-115">Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-115">The following names are reserved:  events, operationsMonitoringEvents, fileNotifications, $default.</span></span> <span data-ttu-id="a6c6c-116">Endpunktnamen müssen über Endpunkttypen eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-116">Endpoint names must be unique across endpoint types.</span></span>  <span data-ttu-id="a6c6c-117">Der Name muss nicht identisch mit dem tatsächlichen Themanamen sein.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-117">The name need not be the same as the actual topic name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a6c6c-118">Ruft ab oder legt den Namen der Ressourcengruppe des Servicebus-Thema-Endpunkt fest.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-118">Gets or sets the name of the resource group of the service bus topic endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="a6c6c-119">Ruft ab oder legt die Abonnement-ID des Servicebus-Thema-Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-119">Gets or sets the subscription identifier of the service bus topic endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingServiceBusTopicEndpointProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingServiceBusTopicEndpointProperties.Validate " />
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
            <span data-ttu-id="a6c6c-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a6c6c-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a6c6c-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a6c6c-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>