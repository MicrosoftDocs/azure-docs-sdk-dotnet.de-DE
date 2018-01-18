<Type Name="ISearchServiceClient" FullName="Microsoft.Azure.Search.ISearchServiceClient">
  <TypeSignature Language="C#" Value="public interface ISearchServiceClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISearchServiceClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.ISearchServiceClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISearchServiceClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type ISearchServiceClient = interface&#xA;    interface IDisposable" />
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
            <span data-ttu-id="dbdd2-101">Client, der zum Verwalten und Abfragen von Indizes und Dokumente, sowie andere Ressourcen, auf ein Azure-Suchdienst verwalten verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-101">Client that can be used to manage and query indexes and documents, as well as manage other resources, on an Azure Search service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Search.ISearchServiceClient.AcceptLanguage" />
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
            <span data-ttu-id="dbdd2-102">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Search.ISearchServiceClient.ApiVersion" />
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
            <span data-ttu-id="dbdd2-103">Client-API-Version.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-103">Client Api Version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Search.ISearchServiceClient.Credentials" />
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
            <span data-ttu-id="dbdd2-104">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-104">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataSources">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IDataSourcesOperations DataSources { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IDataSourcesOperations DataSources" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.DataSources" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataSources As IDataSourcesOperations" />
      <MemberSignature Language="F#" Value="member this.DataSources : Microsoft.Azure.Search.IDataSourcesOperations" Usage="Microsoft.Azure.Search.ISearchServiceClient.DataSources" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IDataSourcesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbdd2-105">Ruft die IDataSourcesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-105">Gets the IDataSourcesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchServiceClient.DeserializationSettings" />
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
            <span data-ttu-id="dbdd2-106">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-106">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchServiceClient.GenerateClientRequestId" />
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
            <span data-ttu-id="dbdd2-107">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-107">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="dbdd2-108">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-108">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IIndexersOperations Indexers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IIndexersOperations Indexers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.Indexers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Indexers As IIndexersOperations" />
      <MemberSignature Language="F#" Value="member this.Indexers : Microsoft.Azure.Search.IIndexersOperations" Usage="Microsoft.Azure.Search.ISearchServiceClient.Indexers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IIndexersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbdd2-109">Ruft die IIndexersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-109">Gets the IIndexersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Indexes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.IIndexesOperations Indexes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.IIndexesOperations Indexes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.Indexes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Indexes As IIndexesOperations" />
      <MemberSignature Language="F#" Value="member this.Indexes : Microsoft.Azure.Search.IIndexesOperations" Usage="Microsoft.Azure.Search.ISearchServiceClient.Indexes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.IIndexesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbdd2-110">Ruft die IIndexesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-110">Gets the IIndexesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.ISearchServiceClient.LongRunningOperationRetryTimeout" />
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
            <span data-ttu-id="dbdd2-111">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-111">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="dbdd2-112">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-112">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.SearchCredentials SearchCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.SearchCredentials SearchCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.SearchCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SearchCredentials As SearchCredentials" />
      <MemberSignature Language="F#" Value="member this.SearchCredentials : Microsoft.Azure.Search.SearchCredentials" Usage="Microsoft.Azure.Search.ISearchServiceClient.SearchCredentials" />
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
            <span data-ttu-id="dbdd2-113">Ruft die Anmeldeinformationen zur Authentifizierung beim Azure-Suchdienst ab.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-113">Gets the credentials used to authenticate to an Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchDnsSuffix">
      <MemberSignature Language="C#" Value="public string SearchDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.SearchDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.SearchDnsSuffix : string with get, set" Usage="Microsoft.Azure.Search.ISearchServiceClient.SearchDnsSuffix" />
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
            <span data-ttu-id="dbdd2-114">Das DNS-Suffix des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-114">The DNS suffix of the Azure Search service.</span></span> <span data-ttu-id="dbdd2-115">Der Standardwert ist.Search.Windows.NET"lauten.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-115">The default is search.windows.net.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchServiceName">
      <MemberSignature Language="C#" Value="public string SearchServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.SearchServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchServiceName As String" />
      <MemberSignature Language="F#" Value="member this.SearchServiceName : string with get, set" Usage="Microsoft.Azure.Search.ISearchServiceClient.SearchServiceName" />
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
            <span data-ttu-id="dbdd2-116">Der Name des Azure-Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-116">The name of the Azure Search service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Search.ISearchServiceClient.SerializationSettings" />
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
            <span data-ttu-id="dbdd2-117">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-117">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SynonymMaps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.ISynonymMapsOperations SynonymMaps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.ISynonymMapsOperations SynonymMaps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.ISearchServiceClient.SynonymMaps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SynonymMaps As ISynonymMapsOperations" />
      <MemberSignature Language="F#" Value="member this.SynonymMaps : Microsoft.Azure.Search.ISynonymMapsOperations" Usage="Microsoft.Azure.Search.ISearchServiceClient.SynonymMaps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.ISynonymMapsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbdd2-118">Ruft die ISynonymMapsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="dbdd2-118">Gets the ISynonymMapsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>