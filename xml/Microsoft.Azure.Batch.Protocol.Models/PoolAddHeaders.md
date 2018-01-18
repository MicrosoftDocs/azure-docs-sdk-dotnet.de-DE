<Type Name="PoolAddHeaders" FullName="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders">
  <TypeSignature Language="C#" Value="public class PoolAddHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolAddHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolAddHeaders" />
  <TypeSignature Language="F#" Value="type PoolAddHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6991d-101">Definiert die Header für hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="6991d-101">Defines headers for Add operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.#ctor" />
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
            <span data-ttu-id="6991d-102">Initialisiert eine neue Instanz der PoolAddHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6991d-102">Initializes a new instance of the PoolAddHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolAddHeaders (Nullable&lt;Guid&gt; clientRequestId = null, Nullable&lt;Guid&gt; requestId = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, string dataServiceId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; clientRequestId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestId, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, string dataServiceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.#ctor(System.Nullable{System.Guid},System.Nullable{System.Guid},System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional clientRequestId As Nullable(Of Guid) = null, Optional requestId As Nullable(Of Guid) = null, Optional eTag As String = null, Optional lastModified As Nullable(Of DateTime) = null, Optional dataServiceId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders : Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders" Usage="new Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders (clientRequestId, requestId, eTag, lastModified, dataServiceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRequestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="dataServiceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientRequestId"><span data-ttu-id="6991d-103">Die Client-Request-Id vom Client bereitgestellt wird, während der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="6991d-103">The client-request-id provided by the client during the request.</span></span> <span data-ttu-id="6991d-104">Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".</span><span class="sxs-lookup"><span data-stu-id="6991d-104">This will be returned only if the return-client-request-id parameter was set to true.</span></span></param>
        <param name="requestId"><span data-ttu-id="6991d-105">Ein eindeutiger Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="6991d-105">A unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="6991d-106">Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden.</span><span class="sxs-lookup"><span data-stu-id="6991d-106">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="6991d-107">Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.</span><span class="sxs-lookup"><span data-stu-id="6991d-107">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span></param>
        <param name="eTag"><span data-ttu-id="6991d-108">Der ETag-HTTP-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="6991d-108">The ETag HTTP response header.</span></span> <span data-ttu-id="6991d-109">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6991d-109">This is an opaque string.</span></span> <span data-ttu-id="6991d-110">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="6991d-110">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="6991d-111">Insbesondere können Sie das ETag in eines der If-Modified-Since, If-Unmodified-Since, If-Match- oder If-None-Match-Header übergeben.</span><span class="sxs-lookup"><span data-stu-id="6991d-111">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span></param>
        <param name="lastModified"><span data-ttu-id="6991d-112">Der Zeitpunkt der letzten Ressourcenänderung.</span><span class="sxs-lookup"><span data-stu-id="6991d-112">The time at which the resource was last modified.</span></span></param>
        <param name="dataServiceId"><span data-ttu-id="6991d-113">Die OData-ID der Ressource, auf die die Anforderung angewendet, werden soll.</span><span class="sxs-lookup"><span data-stu-id="6991d-113">The OData ID of the resource to which the request applied.</span></span></param>
        <summary>
            <span data-ttu-id="6991d-114">Initialisiert eine neue Instanz der PoolAddHeaders-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6991d-114">Initializes a new instance of the PoolAddHeaders class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; ClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; ClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.ClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.ClientRequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.ClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="client-request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6991d-115">Ruft ab oder legt die vom Client bei der Anforderung angegebene Client-Request-Id.</span><span class="sxs-lookup"><span data-stu-id="6991d-115">Gets or sets the client-request-id provided by the client during the request.</span></span> <span data-ttu-id="6991d-116">Dies wird zurückgegeben, nur, wenn die Return-Client-Request-Id-Parameter festgelegt auf "true".</span><span class="sxs-lookup"><span data-stu-id="6991d-116">This will be returned only if the return-client-request-id parameter was set to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataServiceId">
      <MemberSignature Language="C#" Value="public string DataServiceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataServiceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.DataServiceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DataServiceId As String" />
      <MemberSignature Language="F#" Value="member this.DataServiceId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.DataServiceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DataServiceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6991d-117">Ruft ab oder legt die OData-ID der Ressource, auf die die Anforderung angewendet.</span><span class="sxs-lookup"><span data-stu-id="6991d-117">Gets or sets the OData ID of the resource to which the request applied.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ETag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6991d-118">Ruft ab oder legt den ETag-HTTP-Antwortheader.</span><span class="sxs-lookup"><span data-stu-id="6991d-118">Gets or sets the ETag HTTP response header.</span></span> <span data-ttu-id="6991d-119">Dies ist eine nicht transparente Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="6991d-119">This is an opaque string.</span></span> <span data-ttu-id="6991d-120">Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat.</span><span class="sxs-lookup"><span data-stu-id="6991d-120">You can use it to detect whether the resource has changed between requests.</span></span> <span data-ttu-id="6991d-121">Insbesondere können Sie das ETag in eines der If-Modified-Since, If-Unmodified-Since, If-Match- oder If-None-Match-Header übergeben.</span><span class="sxs-lookup"><span data-stu-id="6991d-121">In particular, you can pass the ETag to one of the If-Modified-Since, If-Unmodified-Since, If-Match or If-None-Match headers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.LastModified" />
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
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="Last-Modified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6991d-122">Ruft ab oder legt die Zeit, zu der die Ressource zuletzt geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="6991d-122">Gets or sets the time at which the resource was last modified.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.RequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.PoolAddHeaders.RequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="request-id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6991d-123">Ermittelt oder definiert einen eindeutigen Bezeichner für die Anforderung, die an der Batch-Dienst vorgenommen wurde.</span><span class="sxs-lookup"><span data-stu-id="6991d-123">Gets or sets a unique identifier for the request that was made to the Batch service.</span></span> <span data-ttu-id="6991d-124">Wenn bei einer Anforderung kontinuierlich ein Fehler auftritt, obwohl die Anforderung ordnungsgemäß formuliert ist, können Sie den Fehler unter Angabe dieses Werts an Microsoft melden.</span><span class="sxs-lookup"><span data-stu-id="6991d-124">If a request is consistently failing and you have verified that the request is properly formulated, you may use this value to report the error to Microsoft.</span></span> <span data-ttu-id="6991d-125">Enthalten Sie in Ihrem Bericht dem Wert des diese Anforderungs-ID, die ungefähre Zeit, dass die Anforderung wurde versucht, das Batch-Konto für die die Anforderung gestellt wurde und die Region, der Konto befindet.</span><span class="sxs-lookup"><span data-stu-id="6991d-125">In your report, include the value of this request ID, the approximate time that the request was made, the Batch account against which the request was made, and the region that account resides in.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>