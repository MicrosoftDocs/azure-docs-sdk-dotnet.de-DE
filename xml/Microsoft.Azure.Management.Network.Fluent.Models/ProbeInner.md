<Type Name="ProbeInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner">
  <TypeSignature Language="C#" Value="public class ProbeInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProbeInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ProbeInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ProbeInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="59730-101">Ein Load Balancer-Test.</span><span class="sxs-lookup"><span data-stu-id="59730-101">A load balancer probe.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="59730-102">Initialisiert eine neue Instanz der ProbeInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="59730-102">Initializes a new instance of the ProbeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProbeInner (string protocol, int port, string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules = null, Nullable&lt;int&gt; intervalInSeconds = null, Nullable&lt;int&gt; numberOfProbes = null, string requestPath = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, int32 port, string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; loadBalancingRules, valuetype System.Nullable`1&lt;int32&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int32&gt; numberOfProbes, string requestPath, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.#ctor(System.String,System.Int32,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ResourceManager.Fluent.SubResource},System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, port As Integer, Optional id As String = null, Optional loadBalancingRules As IList(Of SubResource) = null, Optional intervalInSeconds As Nullable(Of Integer) = null, Optional numberOfProbes As Nullable(Of Integer) = null, Optional requestPath As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner : string * int * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner (protocol, port, id, loadBalancingRules, intervalInSeconds, numberOfProbes, requestPath, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numberOfProbes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="requestPath" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="59730-103">Das Protokoll des Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="59730-103">The protocol of the end point.</span></span> <span data-ttu-id="59730-104">Mögliche Werte sind: "Http" oder "Tcp".</span><span class="sxs-lookup"><span data-stu-id="59730-104">Possible values are: 'Http' or 'Tcp'.</span></span> <span data-ttu-id="59730-105">Wenn "Tcp" angegeben wird, ist eine empfangene Bestätigung erforderlich, damit der Test erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="59730-105">If 'Tcp' is specified, a received ACK is required for the probe to be successful.</span></span> <span data-ttu-id="59730-106">Wenn "Http" angegeben wird, eine 200 OK-Antwort von der gibt der URI ist erforderlich, damit der Test erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="59730-106">If 'Http' is specified, a 200 OK response from the specifies URI is required for the probe to be successful.</span></span> <span data-ttu-id="59730-107">Folgende Werte sind möglich: "Http", "Tcp"</span><span class="sxs-lookup"><span data-stu-id="59730-107">Possible values include: 'Http', 'Tcp'</span></span></param>
        <param name="port"><span data-ttu-id="59730-108">Der Port für die Übertragung des Tests.</span><span class="sxs-lookup"><span data-stu-id="59730-108">The port for communicating the probe.</span></span> <span data-ttu-id="59730-109">Mögliche Werte reichen von 1 bis einschließlich 65535.</span><span class="sxs-lookup"><span data-stu-id="59730-109">Possible values range from 1 to 65535, inclusive.</span></span></param>
        <param name="id">To be added.</param>
        <param name="loadBalancingRules"><span data-ttu-id="59730-110">Der Load Balancer-Regeln, die diesen Test verwenden.</span><span class="sxs-lookup"><span data-stu-id="59730-110">The load balancer rules that use this probe.</span></span></param>
        <param name="intervalInSeconds"><span data-ttu-id="59730-111">Das Intervall in Sekunden, in dem der Endpunkt auf den Integritätsstatus getestet werden soll.</span><span class="sxs-lookup"><span data-stu-id="59730-111">The interval, in seconds, for how frequently to probe the endpoint for health status.</span></span> <span data-ttu-id="59730-112">In der Regel ist das Intervall etwas kleiner als die Hälfte des zugeordneten Zeitlimits (in Sekunden). Dies ermöglicht die Durchführung von zwei vollständigen Tests, bevor die Instanz von der Rotation ausgenommen wird.</span><span class="sxs-lookup"><span data-stu-id="59730-112">Typically, the interval is slightly less than half the allocated timeout period (in seconds) which allows two full probes before taking the instance out of rotation.</span></span> <span data-ttu-id="59730-113">Der Standardwert beträgt 15, der Mindestwert 5.</span><span class="sxs-lookup"><span data-stu-id="59730-113">The default value is 15, the minimum value is 5.</span></span></param>
        <param name="numberOfProbes"><span data-ttu-id="59730-114">Die Anzahl der Prüfpunkte Where auf, wenn keine Antwort führt dazu, beenden die weiteren Datenverkehr an den Endpunkt gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="59730-114">The number of probes where if no response, will result in stopping further traffic from being delivered to the endpoint.</span></span> <span data-ttu-id="59730-115">Diese Werte zulässt, die ausgeführt werden Endpunkte aus der Rotation schneller oder langsamer als die typischen Zeiten in Azure.</span><span class="sxs-lookup"><span data-stu-id="59730-115">This values allows endpoints to be taken out of rotation faster or slower than the typical times used in Azure.</span></span></param>
        <param name="requestPath"><span data-ttu-id="59730-116">Der URI, mit dem der Integritätsstatus über den virtuellen Computer angefordert wird.</span><span class="sxs-lookup"><span data-stu-id="59730-116">The URI used for requesting health status from the VM.</span></span> <span data-ttu-id="59730-117">Pfad ist erforderlich, wenn ein Protokoll auf http festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="59730-117">Path is required if a protocol is set to http.</span></span>
            <span data-ttu-id="59730-118">Andernfalls ist die Angabe nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="59730-118">Otherwise, it is not allowed.</span></span> <span data-ttu-id="59730-119">Es gibt keinen Standardwert.</span><span class="sxs-lookup"><span data-stu-id="59730-119">There is no default value.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="59730-120">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="59730-120">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="59730-121">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="59730-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="59730-122">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="59730-122">Gets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="59730-123">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="59730-123">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="59730-124">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="59730-124">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="59730-125">Initialisiert eine neue Instanz der ProbeInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="59730-125">Initializes a new instance of the ProbeInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-126">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="59730-126">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-127">Ruft ab oder legt das Intervall in Sekunden an, wie häufig den Endpunkt für den Integritätsstatus Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="59730-127">Gets or sets the interval, in seconds, for how frequently to probe the endpoint for health status.</span></span> <span data-ttu-id="59730-128">In der Regel ist das Intervall etwas kleiner als die Hälfte des zugeordneten Zeitlimits (in Sekunden). Dies ermöglicht die Durchführung von zwei vollständigen Tests, bevor die Instanz von der Rotation ausgenommen wird.</span><span class="sxs-lookup"><span data-stu-id="59730-128">Typically, the interval is slightly less than half the allocated timeout period (in seconds) which allows two full probes before taking the instance out of rotation.</span></span>
            <span data-ttu-id="59730-129">Der Standardwert beträgt 15, der Mindestwert 5.</span><span class="sxs-lookup"><span data-stu-id="59730-129">The default value is 15, the minimum value is 5.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancingRules As IList(Of SubResource)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ResourceManager.Fluent.SubResource&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-130">Ruft den Load Balancer-Regeln, die diesen Test verwenden.</span><span class="sxs-lookup"><span data-stu-id="59730-130">Gets the load balancer rules that use this probe.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="59730-131">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="59730-131">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="59730-132">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="59730-132">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfProbes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfProbes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfProbes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfProbes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.NumberOfProbes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfProbes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-133">Ruft ab oder legt die Anzahl von Where Prüfpunkte, wenn keine Antwort führt zu Datenverkehr an den Endpunkt gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="59730-133">Gets or sets the number of probes where if no response, will result in stopping further traffic from being delivered to the endpoint.</span></span>
            <span data-ttu-id="59730-134">Diese Werte zulässt, die ausgeführt werden Endpunkte aus der Rotation schneller oder langsamer als die typischen Zeiten in Azure.</span><span class="sxs-lookup"><span data-stu-id="59730-134">This values allows endpoints to be taken out of rotation faster or slower than the typical times used in Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public int Port { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberSignature Language="VB.NET" Value="Public Property Port As Integer" />
      <MemberSignature Language="F#" Value="member this.Port : int with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-135">Ruft ab oder legt den Port für die Kommunikation mit der Überprüfung.</span><span class="sxs-lookup"><span data-stu-id="59730-135">Gets or sets the port for communicating the probe.</span></span> <span data-ttu-id="59730-136">Mögliche Werte reichen von 1 bis einschließlich 65535.</span><span class="sxs-lookup"><span data-stu-id="59730-136">Possible values range from 1 to 65535, inclusive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-137">Ruft ab oder legt das Protokoll des Endpunkts an.</span><span class="sxs-lookup"><span data-stu-id="59730-137">Gets or sets the protocol of the end point.</span></span> <span data-ttu-id="59730-138">Mögliche Werte sind: "Http" oder "Tcp".</span><span class="sxs-lookup"><span data-stu-id="59730-138">Possible values are: 'Http' or 'Tcp'.</span></span> <span data-ttu-id="59730-139">Wenn "Tcp" angegeben wird, ist eine empfangene Bestätigung erforderlich, damit der Test erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="59730-139">If 'Tcp' is specified, a received ACK is required for the probe to be successful.</span></span> <span data-ttu-id="59730-140">Wenn "Http" angegeben wird, eine 200 OK-Antwort von der gibt der URI ist erforderlich, damit der Test erfolgreich ist.</span><span class="sxs-lookup"><span data-stu-id="59730-140">If 'Http' is specified, a 200 OK response from the specifies URI is required for the probe to be successful.</span></span> <span data-ttu-id="59730-141">Folgende Werte sind möglich: "Http", "Tcp"</span><span class="sxs-lookup"><span data-stu-id="59730-141">Possible values include: 'Http', 'Tcp'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="59730-142">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="59730-142">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="59730-143">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="59730-143">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestPath">
      <MemberSignature Language="C#" Value="public string RequestPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestPath As String" />
      <MemberSignature Language="F#" Value="member this.RequestPath : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.RequestPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="59730-144">Ruft ab oder legt den URI für die Anforderung des Integritätsstatus des virtuellen Computers verwendet.</span><span class="sxs-lookup"><span data-stu-id="59730-144">Gets or sets the URI used for requesting health status from the VM.</span></span>
            <span data-ttu-id="59730-145">Pfad ist erforderlich, wenn ein Protokoll auf http festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="59730-145">Path is required if a protocol is set to http.</span></span> <span data-ttu-id="59730-146">Andernfalls ist die Angabe nicht zulässig.</span><span class="sxs-lookup"><span data-stu-id="59730-146">Otherwise, it is not allowed.</span></span> <span data-ttu-id="59730-147">Es gibt keinen Standardwert.</span><span class="sxs-lookup"><span data-stu-id="59730-147">There is no default value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="probeInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="59730-148">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="59730-148">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="59730-149">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="59730-149">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>