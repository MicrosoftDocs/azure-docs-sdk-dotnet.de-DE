<Type Name="ApplicationGatewayProbe" FullName="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe">
  <TypeSignature Language="C#" Value="public class ApplicationGatewayProbe : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ApplicationGatewayProbe extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe" />
  <TypeSignature Language="VB.NET" Value="Public Class ApplicationGatewayProbe&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ApplicationGatewayProbe = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f137c-101">Prüfpunkt für das Anwendungsgateway.</span><span class="sxs-lookup"><span data-stu-id="f137c-101">Probe of the application gateway.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbe ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f137c-102">Initialisiert eine neue Instanz der ApplicationGatewayProbe-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f137c-102">Initializes a new instance of the ApplicationGatewayProbe class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationGatewayProbe (string id = null, string protocol = null, string host = null, string path = null, Nullable&lt;int&gt; interval = null, Nullable&lt;int&gt; timeout = null, Nullable&lt;int&gt; unhealthyThreshold = null, Nullable&lt;bool&gt; pickHostNameFromBackendHttpSettings = null, Nullable&lt;int&gt; minServers = null, Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch match = null, string provisioningState = null, string name = null, string etag = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string protocol, string host, string path, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;int32&gt; unhealthyThreshold, valuetype System.Nullable`1&lt;bool&gt; pickHostNameFromBackendHttpSettings, valuetype System.Nullable`1&lt;int32&gt; minServers, class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch match, string provisioningState, string name, string etag, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional protocol As String = null, Optional host As String = null, Optional path As String = null, Optional interval As Nullable(Of Integer) = null, Optional timeout As Nullable(Of Integer) = null, Optional unhealthyThreshold As Nullable(Of Integer) = null, Optional pickHostNameFromBackendHttpSettings As Nullable(Of Boolean) = null, Optional minServers As Nullable(Of Integer) = null, Optional match As ApplicationGatewayProbeHealthResponseMatch = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe : string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe" Usage="new Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe (id, protocol, host, path, interval, timeout, unhealthyThreshold, pickHostNameFromBackendHttpSettings, minServers, match, provisioningState, name, etag, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="unhealthyThreshold" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="pickHostNameFromBackendHttpSettings" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="minServers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="match" Type="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f137c-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="f137c-103">Resource ID.</span></span></param>
        <param name="protocol"><span data-ttu-id="f137c-104">Protokoll.</span><span class="sxs-lookup"><span data-stu-id="f137c-104">Protocol.</span></span> <span data-ttu-id="f137c-105">Folgende Werte sind möglich: "Http", "Https"</span><span class="sxs-lookup"><span data-stu-id="f137c-105">Possible values include: 'Http', 'Https'</span></span></param>
        <param name="host"><span data-ttu-id="f137c-106">Hostname, der die Überprüfung zu senden.</span><span class="sxs-lookup"><span data-stu-id="f137c-106">Host name to send the probe to.</span></span></param>
        <param name="path"><span data-ttu-id="f137c-107">Relative Pfad der Prüfpunkts.</span><span class="sxs-lookup"><span data-stu-id="f137c-107">Relative path of probe.</span></span> <span data-ttu-id="f137c-108">Gültiger Pfad beginnt mit "/".</span><span class="sxs-lookup"><span data-stu-id="f137c-108">Valid path starts from '/'.</span></span> <span data-ttu-id="f137c-109">Prüfpunkt wird gesendet, um &lt;Protokoll&gt;://&lt;Host&gt;:&lt;Port&gt;&lt;Pfad&gt;</span><span class="sxs-lookup"><span data-stu-id="f137c-109">Probe is sent to &lt;Protocol&gt;://&lt;host&gt;:&lt;port&gt;&lt;path&gt;</span></span></param>
        <param name="interval"><span data-ttu-id="f137c-110">Die Untersuchung verwendeten Intervall in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-110">The probing interval in seconds.</span></span> <span data-ttu-id="f137c-111">Dies ist das Zeitintervall zwischen zwei aufeinanderfolgenden Überprüfungen.</span><span class="sxs-lookup"><span data-stu-id="f137c-111">This is the time interval between two consecutive probes.</span></span> <span data-ttu-id="f137c-112">Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-112">Acceptable values are from 1 second to 86400 seconds.</span></span></param>
        <param name="timeout"><span data-ttu-id="f137c-113">das Test-Timeout in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-113">the probe timeout in seconds.</span></span> <span data-ttu-id="f137c-114">Prüfpunkt markiert als fehlgeschlagen eingestuft, wenn Sie mit diesen Timeouts keine gültige Antwort empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="f137c-114">Probe marked as failed if valid response is not received with this timeout period.</span></span>
            <span data-ttu-id="f137c-115">Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-115">Acceptable values are from 1 second to 86400 seconds.</span></span></param>
        <param name="unhealthyThreshold"><span data-ttu-id="f137c-116">Anzahl der Wiederholungsversuche des Prüfpunkts.</span><span class="sxs-lookup"><span data-stu-id="f137c-116">The probe retry count.</span></span> <span data-ttu-id="f137c-117">Back-End-Server ist ausgefallen gekennzeichnet, nach der Anzahl der aufeinander folgenden Test Fehler UnhealthyThreshold erreicht.</span><span class="sxs-lookup"><span data-stu-id="f137c-117">Backend server is marked down after consecutive probe failure count reaches UnhealthyThreshold.</span></span> <span data-ttu-id="f137c-118">Gültige Werte liegen zwischen 1 Sekunde</span><span class="sxs-lookup"><span data-stu-id="f137c-118">Acceptable values are from 1 second to</span></span>
            20.</param>
        <param name="pickHostNameFromBackendHttpSettings"><span data-ttu-id="f137c-119">Gibt an, ob der Host-Header aus den Back-End-HTTP-Einstellungen ausgewählt werden sollte.</span><span class="sxs-lookup"><span data-stu-id="f137c-119">Whether the host header should be picked from the backend http settings.</span></span> <span data-ttu-id="f137c-120">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="f137c-120">Default value is false.</span></span></param>
        <param name="minServers"><span data-ttu-id="f137c-121">Minimale Anzahl von Servern, die immer fehlerfrei gekennzeichnet sind.</span><span class="sxs-lookup"><span data-stu-id="f137c-121">Minimum number of servers that are always marked healthy.</span></span> <span data-ttu-id="f137c-122">Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="f137c-122">Default value is 0.</span></span></param>
        <param name="match"><span data-ttu-id="f137c-123">Kriterium für eine fehlerfreie überprüfungsantwort zu klassifizieren.</span><span class="sxs-lookup"><span data-stu-id="f137c-123">Criterion for classifying a healthy probe response.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f137c-124">Der Bereitstellungsstatus des Back-End-HTTP-Einstellungsressource.</span><span class="sxs-lookup"><span data-stu-id="f137c-124">Provisioning state of the backend http settings resource.</span></span> <span data-ttu-id="f137c-125">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="f137c-125">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="f137c-126">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="f137c-126">Name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="f137c-127">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="f137c-127">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="f137c-128">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="f137c-128">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="type"><span data-ttu-id="f137c-129">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f137c-129">Type of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="f137c-130">Initialisiert eine neue Instanz der ApplicationGatewayProbe-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f137c-130">Initializes a new instance of the ApplicationGatewayProbe class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f137c-131">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="f137c-131">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-132">Ruft ab, oder legt ihn fest Hostnamen an, die Überprüfung zu senden.</span><span class="sxs-lookup"><span data-stu-id="f137c-132">Gets or sets host name to send the probe to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-133">Ruft ab oder legt die Rückschlüsse auf eventuelle Intervall in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="f137c-133">Gets or sets the probing interval in seconds.</span></span> <span data-ttu-id="f137c-134">Dies ist das Zeitintervall zwischen zwei aufeinanderfolgenden Überprüfungen.</span><span class="sxs-lookup"><span data-stu-id="f137c-134">This is the time interval between two consecutive probes.</span></span> <span data-ttu-id="f137c-135">Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-135">Acceptable values are from 1 second to 86400 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Match">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch Match { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch Match" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Match" />
      <MemberSignature Language="VB.NET" Value="Public Property Match As ApplicationGatewayProbeHealthResponseMatch" />
      <MemberSignature Language="F#" Value="member this.Match : Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Match" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.match")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbeHealthResponseMatch</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-136">Ruft ab, oder legt ihn fest Kriterium für eine fehlerfreie überprüfungsantwort zu klassifizieren.</span><span class="sxs-lookup"><span data-stu-id="f137c-136">Gets or sets criterion for classifying a healthy probe response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinServers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.MinServers" />
      <MemberSignature Language="VB.NET" Value="Public Property MinServers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinServers : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.MinServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-137">Ruft ab oder legt die Mindestanzahl von Servern, die immer fehlerfrei gekennzeichnet sind.</span><span class="sxs-lookup"><span data-stu-id="f137c-137">Gets or sets minimum number of servers that are always marked healthy.</span></span> <span data-ttu-id="f137c-138">Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="f137c-138">Default value is 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f137c-139">Ruft ab oder legt die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="f137c-139">Gets or sets name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="f137c-140">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="f137c-140">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-141">Abrufen oder Festlegen der relativen Pfad der Prüfpunkts.</span><span class="sxs-lookup"><span data-stu-id="f137c-141">Gets or sets relative path of probe.</span></span> <span data-ttu-id="f137c-142">Gültiger Pfad beginnt mit "/".</span><span class="sxs-lookup"><span data-stu-id="f137c-142">Valid path starts from '/'.</span></span>
            <span data-ttu-id="f137c-143">Prüfpunkt wird gesendet, um &amp;Lt; Protokoll&amp;Gt; :/ /&amp;Lt; Host&amp;Gt;:&amp;Lt; Port&amp;Gt;&amp; Lt; Pfad&amp;Gt;</span><span class="sxs-lookup"><span data-stu-id="f137c-143">Probe is sent to &amp;lt;Protocol&amp;gt;://&amp;lt;host&amp;gt;:&amp;lt;port&amp;gt;&amp;lt;path&amp;gt;</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PickHostNameFromBackendHttpSettings">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PickHostNameFromBackendHttpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PickHostNameFromBackendHttpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.PickHostNameFromBackendHttpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property PickHostNameFromBackendHttpSettings As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PickHostNameFromBackendHttpSettings : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.PickHostNameFromBackendHttpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pickHostNameFromBackendHttpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-144">Ruft ab oder legt fest, ob der Host-Header aus der Back-End-HTTP-Einstellungen ausgewählt werden sollte.</span><span class="sxs-lookup"><span data-stu-id="f137c-144">Gets or sets whether the host header should be picked from the backend http settings.</span></span> <span data-ttu-id="f137c-145">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="f137c-145">Default value is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f137c-146">Ruft ab oder legt sie fest.</span><span class="sxs-lookup"><span data-stu-id="f137c-146">Gets or sets protocol.</span></span> <span data-ttu-id="f137c-147">Folgende Werte sind möglich: "Http", "Https"</span><span class="sxs-lookup"><span data-stu-id="f137c-147">Possible values include: 'Http', 'Https'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f137c-148">Ruft ab, oder legt sie fest, der Bereitstellungsstatus des Back-End-HTTP-Einstellungsressource.</span><span class="sxs-lookup"><span data-stu-id="f137c-148">Gets or sets provisioning state of the backend http settings resource.</span></span> <span data-ttu-id="f137c-149">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="f137c-149">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-150">Ruft ab oder legt das Test-Timeout in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="f137c-150">Gets or sets the probe timeout in seconds.</span></span> <span data-ttu-id="f137c-151">Prüfpunkt markiert als fehlgeschlagen eingestuft, wenn Sie mit diesen Timeouts keine gültige Antwort empfangen wird.</span><span class="sxs-lookup"><span data-stu-id="f137c-151">Probe marked as failed if valid response is not received with this timeout period.</span></span>
            <span data-ttu-id="f137c-152">Die zulässigen Werte reichen von 1 Sekunde bis 86400 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="f137c-152">Acceptable values are from 1 second to 86400 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="f137c-153">Ruft ab oder legt den Ressourcentyp aus.</span><span class="sxs-lookup"><span data-stu-id="f137c-153">Gets or sets type of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyThreshold">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UnhealthyThreshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UnhealthyThreshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.UnhealthyThreshold" />
      <MemberSignature Language="VB.NET" Value="Public Property UnhealthyThreshold As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyThreshold : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ApplicationGatewayProbe.UnhealthyThreshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.unhealthyThreshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f137c-154">Ruft ab oder legt die Anzahl von Wiederholungsversuchen Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="f137c-154">Gets or sets the probe retry count.</span></span> <span data-ttu-id="f137c-155">Back-End-Server ist ausgefallen gekennzeichnet, nach der Anzahl der aufeinander folgenden Test Fehler UnhealthyThreshold erreicht.</span><span class="sxs-lookup"><span data-stu-id="f137c-155">Backend server is marked down after consecutive probe failure count reaches UnhealthyThreshold.</span></span>
            <span data-ttu-id="f137c-156">Die zulässigen Werte reichen von 1 Sekunde bis 20.</span><span class="sxs-lookup"><span data-stu-id="f137c-156">Acceptable values are from 1 second to 20.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>