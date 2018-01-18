<Type Name="Endpoint" FullName="Microsoft.Azure.Management.TrafficManager.Models.Endpoint">
  <TypeSignature Language="C#" Value="public class Endpoint" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Endpoint extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Endpoint" />
  <TypeSignature Language="VB.NET" Value="Public Class Endpoint" />
  <TypeSignature Language="F#" Value="type Endpoint = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dbb8e-101">Klasse, die einen Traffic Manager-Endpunkt darstellt.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-101">Class representing a Traffic Manager endpoint.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoint ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-102">Initialisiert eine neue Instanz der Endpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-102">Initializes a new instance of the Endpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoint (string id = null, string name = null, string type = null, string targetResourceId = null, string target = null, string endpointStatus = null, Nullable&lt;long&gt; weight = null, Nullable&lt;long&gt; priority = null, string endpointLocation = null, string endpointMonitorStatus = null, Nullable&lt;long&gt; minChildEndpoints = null, System.Collections.Generic.IList&lt;string&gt; geoMapping = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string targetResourceId, string target, string endpointStatus, valuetype System.Nullable`1&lt;int64&gt; weight, valuetype System.Nullable`1&lt;int64&gt; priority, string endpointLocation, string endpointMonitorStatus, valuetype System.Nullable`1&lt;int64&gt; minChildEndpoints, class System.Collections.Generic.IList`1&lt;string&gt; geoMapping) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,System.String,System.Nullable{System.Int64},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional targetResourceId As String = null, Optional target As String = null, Optional endpointStatus As String = null, Optional weight As Nullable(Of Long) = null, Optional priority As Nullable(Of Long) = null, Optional endpointLocation As String = null, Optional endpointMonitorStatus As String = null, Optional minChildEndpoints As Nullable(Of Long) = null, Optional geoMapping As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Endpoint : string * string * string * string * string * string * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * string * Nullable&lt;int64&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Endpoint" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Endpoint (id, name, type, targetResourceId, target, endpointStatus, weight, priority, endpointLocation, endpointMonitorStatus, minChildEndpoints, geoMapping)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="targetResourceId" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="endpointStatus" Type="System.String" />
        <Parameter Name="weight" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="endpointLocation" Type="System.String" />
        <Parameter Name="endpointMonitorStatus" Type="System.String" />
        <Parameter Name="minChildEndpoints" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="geoMapping" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="dbb8e-103">Ruft ab oder legt die ID des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-103">Gets or sets the ID of the Traffic Manager endpoint.</span></span></param>
        <param name="name"><span data-ttu-id="dbb8e-104">Ruft ab oder legt den Namen des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-104">Gets or sets the name of the Traffic Manager endpoint.</span></span></param>
        <param name="type"><span data-ttu-id="dbb8e-105">Ruft ab oder legt den Endpunkttyp des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-105">Gets or sets the endpoint type of the Traffic Manager endpoint.</span></span></param>
        <param name="targetResourceId"><span data-ttu-id="dbb8e-106">Ruft ab oder legt den Azure-Ressourcen-URI des der des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-106">Gets or sets the Azure Resource URI of the of the endpoint.</span></span>  <span data-ttu-id="dbb8e-107">Gilt nicht für Endpunkte vom Typ "ExternalEndpoints".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-107">Not applicable to endpoints of type 'ExternalEndpoints'.</span></span></param>
        <param name="target"><span data-ttu-id="dbb8e-108">Ruft ab oder legt den vollqualifizierten DNS-Namen des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-108">Gets or sets the fully-qualified DNS name of the endpoint.</span></span>  <span data-ttu-id="dbb8e-109">Traffic Manager gibt diesen Wert zurück, in der DNS-Antworten zur Weiterleitung von Datenverkehr an diesen Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-109">Traffic Manager returns this value in DNS responses to direct traffic to this endpoint.</span></span></param>
        <param name="endpointStatus"><span data-ttu-id="dbb8e-110">Ruft ab oder legt den Status des Endpunkts...</span><span class="sxs-lookup"><span data-stu-id="dbb8e-110">Gets or sets the status of the endpoint..</span></span>  <span data-ttu-id="dbb8e-111">Wenn der Endpunkt aktiviert ist, wird endpunktzuständen verkehrsroutingmethode und in die verkehrsroutingmethode eingeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-111">If the endpoint is Enabled, it is probed for endpoint health and is included in the traffic routing method.</span></span>  <span data-ttu-id="dbb8e-112">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-112">Possible values are 'Enabled' and 'Disabled'.</span></span></param>
        <param name="weight"><span data-ttu-id="dbb8e-113">Ruft ab oder legt die Gewichtung dieses Endpunkts bei Verwendung der verkehrsroutingmethode "Weighted".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-113">Gets or sets the weight of this endpoint when using the 'Weighted' traffic routing method.</span></span> <span data-ttu-id="dbb8e-114">Mögliche Werte liegen zwischen 1 und 1000.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-114">Possible values are from 1 to 1000.</span></span></param>
        <param name="priority"><span data-ttu-id="dbb8e-115">Ruft ab oder legt die Priorität dieses Endpunkts bei Verwendung der verkehrsroutingmethode 'Priority'.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-115">Gets or sets the priority of this endpoint when using the ‘Priority’ traffic routing method.</span></span> <span data-ttu-id="dbb8e-116">Mögliche Werte liegen zwischen 1 und 1000, niedrigere Werte stellen eine höheren Priorität dar.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-116">Possible values are from 1 to 1000, lower values represent higher priority.</span></span> <span data-ttu-id="dbb8e-117">Dieser Parameter ist optional.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-117">This is an optional parameter.</span></span>  <span data-ttu-id="dbb8e-118">Wenn angegeben, muss es auf alle Endpunkte angegeben werden, und zwei Endpunkte nicht denselben Prioritätswert freigeben können.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-118">If specified, it must be specified on all endpoints, and no two endpoints can share the same priority value.</span></span></param>
        <param name="endpointLocation"><span data-ttu-id="dbb8e-119">Gibt den Speicherort der externen oder geschachtelte Endpunkte an, bei Verwendung der verkehrsroutingmethode "Performance".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-119">Specifies the location of the external or nested endpoints when using the ‘Performance’ traffic routing method.</span></span></param>
        <param name="endpointMonitorStatus"><span data-ttu-id="dbb8e-120">Abrufen oder Festlegen der Überwachungsstatus des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-120">Gets or sets the monitoring status of the endpoint.</span></span></param>
        <param name="minChildEndpoints"><span data-ttu-id="dbb8e-121">Ruft ab oder legt die Mindestanzahl von Endpunkten, die im untergeordneten Profil in der Reihenfolge für das übergeordnete-Profil verfügbar angesehen verfügbar sein müssen.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-121">Gets or sets the minimum number of endpoints that must be available in the child profile in order for the parent profile to be considered available.</span></span> <span data-ttu-id="dbb8e-122">Gilt nur für den Endpunkt des Typs "NestedEndpoints".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-122">Only applicable to endpoint of type 'NestedEndpoints'.</span></span></param>
        <param name="geoMapping"><span data-ttu-id="dbb8e-123">Ruft ab oder legt die Liste der Länder/Regionen an diesen Endpunkt zugeordnet werden, wenn die verkehrsroutingmethode "Geografisch" verwenden.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-123">Gets or sets the list of countries/regions mapped to this endpoint when using the ‘Geographic’ traffic routing method.</span></span> <span data-ttu-id="dbb8e-124">Eine vollständige Liste der zulässigen Werte finden Sie in geografisch Traffic Manager-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-124">Please consult Traffic Manager Geographic documentation for a full list of accepted values.</span></span></param>
        <summary>
            <span data-ttu-id="dbb8e-125">Initialisiert eine neue Instanz der Endpoint-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-125">Initializes a new instance of the Endpoint class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointLocation">
      <MemberSignature Language="C#" Value="public string EndpointLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointLocation As String" />
      <MemberSignature Language="F#" Value="member this.EndpointLocation : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-126">Ruft ab oder legt ihn fest, gibt den Speicherort der externen oder geschachtelte Endpunkte bei Verwendung der "Leistung" Datenverkehr Routingmethode.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-126">Gets or sets specifies the location of the external or nested endpoints when using the ‘Performance’ traffic routing method.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointMonitorStatus">
      <MemberSignature Language="C#" Value="public string EndpointMonitorStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointMonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointMonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointMonitorStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointMonitorStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointMonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointMonitorStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-127">Abrufen oder Festlegen der Überwachungsstatus des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-127">Gets or sets the monitoring status of the endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointStatus">
      <MemberSignature Language="C#" Value="public string EndpointStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndpointStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointStatus As String" />
      <MemberSignature Language="F#" Value="member this.EndpointStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.EndpointStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpointStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-128">Ruft ab oder legt den Status des Endpunkts...</span><span class="sxs-lookup"><span data-stu-id="dbb8e-128">Gets or sets the status of the endpoint..</span></span>  <span data-ttu-id="dbb8e-129">Wenn der Endpunkt aktiviert ist, wird endpunktzuständen verkehrsroutingmethode und in die verkehrsroutingmethode eingeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-129">If the endpoint is Enabled, it is probed for endpoint health and is included in the traffic routing method.</span></span>  <span data-ttu-id="dbb8e-130">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-130">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoMapping">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; GeoMapping { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; GeoMapping" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.GeoMapping" />
      <MemberSignature Language="VB.NET" Value="Public Property GeoMapping As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.GeoMapping : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.GeoMapping" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoMapping")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-131">Ruft ab oder legt die Liste der Länder/Regionen an diesen Endpunkt zugeordnet werden, wenn die verkehrsroutingmethode "Geografisch" verwenden.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-131">Gets or sets the list of countries/regions mapped to this endpoint when using the ‘Geographic’ traffic routing method.</span></span> <span data-ttu-id="dbb8e-132">Eine vollständige Liste der zulässigen Werte finden Sie in geografisch Traffic Manager-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-132">Please consult Traffic Manager Geographic documentation for a full list of accepted values.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-133">Ruft ab oder legt die ID des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-133">Gets or sets the ID of the Traffic Manager endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinChildEndpoints">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MinChildEndpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MinChildEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.MinChildEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property MinChildEndpoints As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MinChildEndpoints : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.MinChildEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minChildEndpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-134">Ruft ab oder legt die Mindestanzahl von Endpunkten, die im untergeordneten Profil in der Reihenfolge für das übergeordnete-Profil verfügbar angesehen verfügbar sein müssen.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-134">Gets or sets the minimum number of endpoints that must be available in the child profile in order for the parent profile to be considered available.</span></span> <span data-ttu-id="dbb8e-135">Gilt nur für den Endpunkt des Typs "NestedEndpoints".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-135">Only applicable to endpoint of type 'NestedEndpoints'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="dbb8e-136">Ruft ab oder legt den Namen des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-136">Gets or sets the name of the Traffic Manager endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-137">Ruft ab oder legt die Priorität dieses Endpunkts bei Verwendung der verkehrsroutingmethode 'Priority'.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-137">Gets or sets the priority of this endpoint when using the ‘Priority’ traffic routing method.</span></span> <span data-ttu-id="dbb8e-138">Mögliche Werte liegen zwischen 1 und 1000, niedrigere Werte stellen eine höheren Priorität dar.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-138">Possible values are from 1 to 1000, lower values represent higher priority.</span></span> <span data-ttu-id="dbb8e-139">Dieser Parameter ist optional.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-139">This is an optional parameter.</span></span>  <span data-ttu-id="dbb8e-140">Wenn angegeben, muss es auf alle Endpunkte angegeben werden, und zwei Endpunkte nicht denselben Prioritätswert freigeben können.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-140">If specified, it must be specified on all endpoints, and no two endpoints can share the same priority value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Target">
      <MemberSignature Language="C#" Value="public string Target { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Target" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Target" />
      <MemberSignature Language="VB.NET" Value="Public Property Target As String" />
      <MemberSignature Language="F#" Value="member this.Target : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Target" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.target")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-141">Ruft ab oder legt den vollqualifizierten DNS-Namen des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-141">Gets or sets the fully-qualified DNS name of the endpoint.</span></span>  <span data-ttu-id="dbb8e-142">Traffic Manager gibt diesen Wert zurück, in der DNS-Antworten zur Weiterleitung von Datenverkehr an diesen Endpunkt.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-142">Traffic Manager returns this value in DNS responses to direct traffic to this endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceId">
      <MemberSignature Language="C#" Value="public string TargetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.TargetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceId : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.TargetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-143">Ruft ab oder legt den Azure-Ressourcen-URI des der des Endpunkts.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-143">Gets or sets the Azure Resource URI of the of the endpoint.</span></span>  <span data-ttu-id="dbb8e-144">Gilt nicht für Endpunkte vom Typ "ExternalEndpoints".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-144">Not applicable to endpoints of type 'ExternalEndpoints'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-145">Ruft ab oder legt den Endpunkttyp des Traffic Manager-Endpunkts fest.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-145">Gets or sets the endpoint type of the Traffic Manager endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Weight { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Weight" />
      <MemberSignature Language="VB.NET" Value="Public Property Weight As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Endpoint.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.weight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbb8e-146">Ruft ab oder legt die Gewichtung dieses Endpunkts bei Verwendung der verkehrsroutingmethode "Weighted".</span><span class="sxs-lookup"><span data-stu-id="dbb8e-146">Gets or sets the weight of this endpoint when using the 'Weighted' traffic routing method.</span></span> <span data-ttu-id="dbb8e-147">Mögliche Werte liegen zwischen 1 und 1000.</span><span class="sxs-lookup"><span data-stu-id="dbb8e-147">Possible values are from 1 to 1000.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>