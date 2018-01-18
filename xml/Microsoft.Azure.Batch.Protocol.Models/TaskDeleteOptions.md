<Type Name="TaskDeleteOptions" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions">
  <TypeSignature Language="C#" Value="public class TaskDeleteOptions : Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDeleteOptions extends System.Object implements class Microsoft.Azure.Batch.Protocol.Models.IOptions, class Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDeleteOptions&#xA;Implements ITimeoutOptions" />
  <TypeSignature Language="F#" Value="type TaskDeleteOptions = class&#xA;    interface ITimeoutOptions&#xA;    interface IOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="72965-101">Zusätzliche Parameter für Delete-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="72965-101">Additional parameters for Delete operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDeleteOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="72965-102">Initialisiert eine neue Instanz der TaskDeleteOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="72965-102">Initializes a new instance of the TaskDeleteOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDeleteOptions (Nullable&lt;int&gt; timeout = null, Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;bool&gt; returnClientRequestId = null, Nullable&lt;DateTime&gt; ocpDate = null, string ifMatch = null, string ifNoneMatch = null, Nullable&lt;DateTime&gt; ifModifiedSince = null, Nullable&lt;DateTime&gt; ifUnmodifiedSince = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; timeout, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;bool&gt; returnClientRequestId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ocpDate, string ifMatch, string ifNoneMatch, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifModifiedSince, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ifUnmodifiedSince) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.#ctor(System.Nullable{System.Int32},System.Nullable{System.Guid},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeout As Nullable(Of Integer) = null, Optional clientRequestId As Nullable(Of Guid) = null, Optional returnClientRequestId As Nullable(Of Boolean) = null, Optional ocpDate As Nullable(Of DateTime) = null, Optional ifMatch As String = null, Optional ifNoneMatch As String = null, Optional ifModifiedSince As Nullable(Of DateTime) = null, Optional ifUnmodifiedSince As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions : Nullable&lt;int&gt; * Nullable&lt;Guid&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions (timeout, clientRequestId, returnClientRequestId, ocpDate, ifMatch, ifNoneMatch, ifModifiedSince, ifUnmodifiedSince)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeout" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="returnClientRequestId" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="ocpDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="ifModifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ifUnmodifiedSince" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="timeout"><span data-ttu-id="72965-103">Die maximale Zeit, die der Server verarbeitet die Anforderung in Sekunden aufwenden kann.</span><span class="sxs-lookup"><span data-stu-id="72965-103">The maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="72965-104">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="72965-104">The default is 30 seconds.</span></span></param>
        <param name="clientRequestId"><span data-ttu-id="72965-105">Die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="72965-105">The caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span></param>
        <param name="returnClientRequestId"><span data-ttu-id="72965-106">Gibt an, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="72965-106">Whether the server should return the client-request-id in the response.</span></span></param>
        <param name="ocpDate"><span data-ttu-id="72965-107">Die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-107">The time the request was issued.</span></span> <span data-ttu-id="72965-108">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="72965-108">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span></param>
        <param name="ifMatch"><span data-ttu-id="72965-109">Ein ETag-Wert, der Version der Ressource dem Client bekannt zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="72965-109">An ETag value associated with the version of the resource known to the client.</span></span> <span data-ttu-id="72965-110">Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst genau dem vom Client angegebenen Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="72965-110">The operation will be performed only if the resource's current ETag on the service exactly matches the value specified by the client.</span></span></param>
        <param name="ifNoneMatch"><span data-ttu-id="72965-111">Ein ETag-Wert, der Version der Ressource dem Client bekannt zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="72965-111">An ETag value associated with the version of the resource known to the client.</span></span> <span data-ttu-id="72965-112">Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst nicht mit den vom Client angegebenen Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="72965-112">The operation will be performed only if the resource's current ETag on the service does not match the value specified by the client.</span></span></param>
        <param name="ifModifiedSince"><span data-ttu-id="72965-113">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="72965-113">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="72965-114">Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-114">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span></param>
        <param name="ifUnmodifiedSince"><span data-ttu-id="72965-115">Ein Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="72965-115">A timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="72965-116">Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-116">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span></param>
        <summary>
            <span data-ttu-id="72965-117">Initialisiert eine neue Instanz der TaskDeleteOptions-Klasse.</span><span class="sxs-lookup"><span data-stu-id="72965-117">Initializes a new instance of the TaskDeleteOptions class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.ClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-118">Ruft ab oder legt die vom Aufrufer generierte Anforderungsidentität in Form einer GUID ohne Dekoration wie etwa geschweifte Klammern ein, z. B. 9C4D50EE 2-d 56-CD 3-8152-34347DC9F2B0 4.</span><span class="sxs-lookup"><span data-stu-id="72965-118">Gets or sets the caller-generated request identity, in the form of a GUID with no decoration such as curly braces, e.g. 9C4D50EE-2D56-4CD3-8152-34347DC9F2B0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfMatch">
      <MemberSignature Language="C#" Value="public string IfMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfMatch : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-119">Ruft ab oder legt einen ETag-Wert, der die Version der Ressource dem Client bekannt zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="72965-119">Gets or sets an ETag value associated with the version of the resource known to the client.</span></span> <span data-ttu-id="72965-120">Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst genau dem vom Client angegebenen Wert entspricht.</span><span class="sxs-lookup"><span data-stu-id="72965-120">The operation will be performed only if the resource's current ETag on the service exactly matches the value specified by the client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfModifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfModifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfModifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfModifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfModifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfModifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfModifiedSince" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-121">Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="72965-121">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="72965-122">Der Vorgang wird ausgeführt werden, nur, wenn die Ressource für den Dienst seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-122">The operation will be performed only if the resource on the service has been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfNoneMatch">
      <MemberSignature Language="C#" Value="public string IfNoneMatch { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IfNoneMatch" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfNoneMatch" />
      <MemberSignature Language="VB.NET" Value="Public Property IfNoneMatch As String" />
      <MemberSignature Language="F#" Value="member this.IfNoneMatch : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfNoneMatch" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-123">Ruft ab oder legt einen ETag-Wert, der die Version der Ressource dem Client bekannt zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="72965-123">Gets or sets an ETag value associated with the version of the resource known to the client.</span></span> <span data-ttu-id="72965-124">Der Vorgang wird ausgeführt werden, nur dann, wenn das aktuelle ETag der Ressource für den Dienst nicht mit den vom Client angegebenen Wert übereinstimmt.</span><span class="sxs-lookup"><span data-stu-id="72965-124">The operation will be performed only if the resource's current ETag on the service does not match the value specified by the client.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IfUnmodifiedSince">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; IfUnmodifiedSince { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; IfUnmodifiedSince" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfUnmodifiedSince" />
      <MemberSignature Language="VB.NET" Value="Public Property IfUnmodifiedSince As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.IfUnmodifiedSince : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.IfUnmodifiedSince" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-125">Ermittelt oder definiert einen Zeitstempel, der angibt, den Zeitpunkt des letzten Änderung der Ressource an den Client bezeichnet.</span><span class="sxs-lookup"><span data-stu-id="72965-125">Gets or sets a timestamp indicating the last modified time of the resource known to the client.</span></span> <span data-ttu-id="72965-126">Der Vorgang wird ausgeführt werden, nur dann, wenn die Ressource für den Dienst nicht seit dem angegebenen Uhrzeit geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-126">The operation will be performed only if the resource on the service has not been modified since the specified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OcpDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OcpDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OcpDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.OcpDate" />
      <MemberSignature Language="VB.NET" Value="Public Property OcpDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OcpDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.OcpDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.DateTimeRfc1123JsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-127">Ruft ab oder legt die Zeit, die die Anforderung ausgegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="72965-127">Gets or sets the time the request was issued.</span></span> <span data-ttu-id="72965-128">Clientbibliotheken festlegen, in der Regel um die aktuelle Systemuhrzeit; Legen Sie sie explizit die REST-API direkt aufrufen.</span><span class="sxs-lookup"><span data-stu-id="72965-128">Client libraries typically set this to the current system clock time; set it explicitly if you are calling the REST API directly.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReturnClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReturnClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReturnClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.ReturnClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReturnClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReturnClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.ReturnClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.IOptions.ReturnClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-129">Ruft ab oder legt sie fest, ob der Server die Client-Request-Id in der Antwort zurückgeben soll.</span><span class="sxs-lookup"><span data-stu-id="72965-129">Gets or sets whether the server should return the client-request-id in the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Timeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDeleteOptions.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.Models.ITimeoutOptions.Timeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="72965-130">Ruft ab oder legt die maximale Zeit, dass der Server konsolenmeldungen Verarbeitung der Anforderung in Sekunden fest.</span><span class="sxs-lookup"><span data-stu-id="72965-130">Gets or sets the maximum time that the server can spend processing the request, in seconds.</span></span> <span data-ttu-id="72965-131">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="72965-131">The default is 30 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>