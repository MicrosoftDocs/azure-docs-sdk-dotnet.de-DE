<Type Name="ISearchIndexClient" FullName="Microsoft.Azure.Search.ISearchIndexClient">
  <TypeSignature Language="C#" Value="public interface ISearchIndexClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISearchIndexClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.ISearchIndexClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISearchIndexClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ISearchIndexClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c8979-101">Clients, die verwendet werden kann, zum Abfragen einer Azure Search-Index und hochladen, Zusammenführen oder Löschen von Dokumenten.</span><span class="sxs-lookup"><span data-stu-id="c8979-101">Client that can be used to query an Azure Search index and upload, merge, or delete documents.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-102">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="c8979-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Search.ISearchIndexClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-103">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="c8979-103">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Search.ISearchIndexClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-104">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="c8979-104">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchIndexClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-105">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="c8979-105">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Documents">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IDocumentsOperations Documents { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IDocumentsOperations Documents" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.Documents" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Documents As IDocumentsOperations" />
      <MemberSignature Language="F#" Value="member this.Documents : Microsoft.Azure.Search.IDocumentsOperations" Usage="Microsoft.Azure.Search.ISearchIndexClient.Documents" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IDocumentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-106">Ruft die IDocumentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="c8979-106">Gets the IDocumentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-107">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="c8979-107">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="c8979-108">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="c8979-108">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexName">
      <MemberSignature Language="C#" Value="public string IndexName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IndexName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.IndexName" />
      <MemberSignature Language="VB.NET" Value="Public Property IndexName As String" />
      <MemberSignature Language="F#" Value="member this.IndexName : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.IndexName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-109">Der Name der Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="c8979-109">The name of the Azure Search index.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-110">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c8979-110">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="c8979-111">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="c8979-111">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.SearchCredentials SearchCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.SearchCredentials SearchCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchCredentials As SearchCredentials" />
      <MemberSignature Language="F#" Value="member this.SearchCredentials : Microsoft.Azure.Search.SearchCredentials" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.SearchCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-112">Ruft die Anmeldeinformationen zur Authentifizierung beim Azure-Suchdienst ab.</span><span class="sxs-lookup"><span data-stu-id="c8979-112">Gets the credentials used to authenticate to an Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchDnsSuffix">
      <MemberSignature Language="C#" Value="public string SearchDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.SearchDnsSuffix : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchDnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-113">Das DNS-Suffix des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="c8979-113">The DNS suffix of the Azure Search service.</span></span> <span data-ttu-id="c8979-114">Der Standardwert ist.Search.Windows.NET"lauten.</span><span class="sxs-lookup"><span data-stu-id="c8979-114">The default is search.windows.net.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchServiceName">
      <MemberSignature Language="C#" Value="public string SearchServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SearchServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchServiceName As String" />
      <MemberSignature Language="F#" Value="member this.SearchServiceName : string with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.SearchServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-115">Der Name des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="c8979-115">The name of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchIndexClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-116">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="c8979-116">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDifferentIndex">
      <MemberSignature Language="C#" Value="public void TargetDifferentIndex (string newIndexName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void TargetDifferentIndex(string newIndexName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.ISearchIndexClient.TargetDifferentIndex(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TargetDifferentIndex (newIndexName As String)" />
      <MemberSignature Language="F#" Value="abstract member TargetDifferentIndex : string -&gt; unit" Usage="iSearchIndexClient.TargetDifferentIndex newIndexName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newIndexName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="newIndexName"><span data-ttu-id="c8979-117">Der Name des Indexes, der alle nachfolgende Anforderungen gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c8979-117">The name of the index to which all subsequent requests should be sent.</span></span></param>
        <summary>
            <span data-ttu-id="c8979-118">Ändert die BaseUri dieses Clients einen anderen Index in der gleichen Azure Search-Dienst als Ziel.</span><span class="sxs-lookup"><span data-stu-id="c8979-118">Changes the BaseUri of this client to target a different index in the same Azure Search service.</span></span> <span data-ttu-id="c8979-119">Diese Methode ist nicht threadsicher; Sie müssen sicherstellen, dass keine anderen Threads vor dem Aufruf des Clients verwenden.</span><span class="sxs-lookup"><span data-stu-id="c8979-119">This method is NOT thread-safe; You must guarantee that no other threads are using the client before calling it.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseHttpGetForQueries">
      <MemberSignature Language="C#" Value="public bool UseHttpGetForQueries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool UseHttpGetForQueries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchIndexClient.UseHttpGetForQueries" />
      <MemberSignature Language="VB.NET" Value="Public Property UseHttpGetForQueries As Boolean" />
      <MemberSignature Language="F#" Value="member this.UseHttpGetForQueries : bool with get, set" Usage="Microsoft.Azure.Search.ISearchIndexClient.UseHttpGetForQueries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8979-120">Gibt an, ob der Index-Client sollte Geschäftsgründen Suche verwenden HTTP GET und Anforderungen an die Azure-Suchdienst-REST-API vorschlagen.</span><span class="sxs-lookup"><span data-stu-id="c8979-120">Indicates whether the index client should use HTTP GET for making Search and Suggest requests to the Azure Search REST API.</span></span> <span data-ttu-id="c8979-121">Die Standardeinstellung ist <c>"false"</c>, was bedeutet, dass HTTP POST verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="c8979-121">The default is <c>false</c>, which indicates that HTTP POST will be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>