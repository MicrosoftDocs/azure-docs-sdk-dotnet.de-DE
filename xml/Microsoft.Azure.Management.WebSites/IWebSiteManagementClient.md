<Type Name="IWebSiteManagementClient" FullName="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient">
  <TypeSignature Language="C#" Value="public interface IWebSiteManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebSiteManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebSiteManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IWebSiteManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="73fa2-101">WebSite-Verwaltungsclient</span><span class="sxs-lookup"><span data-stu-id="73fa2-101">WebSite Management Client</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-102">Ruft ab oder legt die bevorzugte Sprache für die Antwort.</span><span class="sxs-lookup"><span data-stu-id="73fa2-102">Gets or sets the preferred language for the response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceCertificateOrders">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations AppServiceCertificateOrders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceCertificateOrders As IAppServiceCertificateOrdersOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceCertificateOrders : Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceCertificateOrders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceCertificateOrdersOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-103">Ruft die IAppServiceCertificateOrdersOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-103">Gets the IAppServiceCertificateOrdersOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironments">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations AppServiceEnvironments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceEnvironments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServiceEnvironments As IAppServiceEnvironmentsOperations" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironments : Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServiceEnvironments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServiceEnvironmentsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-104">Ruft die IAppServiceEnvironmentsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-104">Gets the IAppServiceEnvironmentsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlans">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IAppServicePlansOperations AppServicePlans" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServicePlans" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServicePlans As IAppServicePlansOperations" />
      <MemberSignature Language="F#" Value="member this.AppServicePlans : Microsoft.Azure.Management.WebSites.IAppServicePlansOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.AppServicePlans" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IAppServicePlansOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-105">Ruft die IAppServicePlansOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-105">Gets the IAppServicePlansOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-106">Die Basis-URI des Diensts.</span><span class="sxs-lookup"><span data-stu-id="73fa2-106">The base URI of the service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ICertificatesOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificates As ICertificatesOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.WebSites.ICertificatesOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ICertificatesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-107">Ruft die ICertificatesOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-107">Gets the ICertificatesOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync (string name, string type, Nullable&lt;bool&gt; isFqdn = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt; CheckNameAvailabilityWithHttpMessagesAsync(string name, string type, valuetype System.Nullable`1&lt;bool&gt; isFqdn, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckNameAvailabilityWithHttpMessagesAsync : string * string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;" Usage="iWebSiteManagementClient.CheckNameAvailabilityWithHttpMessagesAsync (name, type, isFqdn, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ResourceNameAvailability&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="isFqdn" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
            <span data-ttu-id="73fa2-108">Der Ressourcenname überprüfen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-108">Resource name to verify.</span></span>
            </param>
        <param name="type">
            <span data-ttu-id="73fa2-109">Ressourcentyp zur Überprüfung verwendet.</span><span class="sxs-lookup"><span data-stu-id="73fa2-109">Resource type used for verification.</span></span> <span data-ttu-id="73fa2-110">Folgende Werte sind möglich: "Website", "Slot", "HostingEnvironment"</span><span class="sxs-lookup"><span data-stu-id="73fa2-110">Possible values include: 'Site', 'Slot', 'HostingEnvironment'</span></span>
            </param>
        <param name="isFqdn">
            <span data-ttu-id="73fa2-111">Ist vollqualifizierte Domänenname.</span><span class="sxs-lookup"><span data-stu-id="73fa2-111">Is fully qualified domain name.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-112">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-112">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-114">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="73fa2-114">Check if a resource name is available.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-115">Überprüfen Sie, ob der Name einer Ressource verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="73fa2-115">Check if a resource name is available.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-116">Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.</span><span class="sxs-lookup"><span data-stu-id="73fa2-116">Credentials needed for the client to connect to Azure.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedWebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations DeletedWebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeletedWebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedWebApps As IDeletedWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.DeletedWebApps : Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeletedWebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDeletedWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-117">Ruft die IDeletedWebAppsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-117">Gets the IDeletedWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-118">Ermittelt oder Json-Deserialisierung Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="73fa2-118">Gets or sets json deserialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Domains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IDomainsOperations Domains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IDomainsOperations Domains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Domains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Domains As IDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.Domains : Microsoft.Azure.Management.WebSites.IDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Domains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-119">Ruft die IDomainsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-119">Gets the IDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-120">Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten.</span><span class="sxs-lookup"><span data-stu-id="73fa2-120">When set to true a unique x-ms-client-request-id value is generated and included in each request.</span></span> <span data-ttu-id="73fa2-121">Der Standardwert ist true.</span><span class="sxs-lookup"><span data-stu-id="73fa2-121">Default is true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; GetPublishingUserWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingUserWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="iWebSiteManagementClient.GetPublishingUserWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-122">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-122">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-124">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="73fa2-124">Gets publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-125">Benutzer ruft veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="73fa2-125">Gets publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync (string sourceControlType, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; GetSourceControlWithHttpMessagesAsync(string sourceControlType, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSourceControlWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControlWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="iWebSiteManagementClient.GetSourceControlWithHttpMessagesAsync (sourceControlType, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="73fa2-126">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="73fa2-126">Type of source control</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-127">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-127">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-129">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="73fa2-129">Gets source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-130">Ruft die Datenquellen-Steuerelements token</span><span class="sxs-lookup"><span data-stu-id="73fa2-130">Gets source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSubscriptionDeploymentLocationsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt; GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSubscriptionDeploymentLocationsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;" Usage="iWebSiteManagementClient.GetSubscriptionDeploymentLocationsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.DeploymentLocations&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-131">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-131">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-133">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="73fa2-133">Gets list of available geo regions plus ministamps</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-134">Ruft die Liste der verfügbaren geografischen Regionen sowie ministamps</span><span class="sxs-lookup"><span data-stu-id="73fa2-134">Gets list of available geo regions plus ministamps</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListGeoRegionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="73fa2-135">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="73fa2-135">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-136">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-136">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-138">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-138">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-139">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-139">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGeoRegionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync (string sku = null, Nullable&lt;bool&gt; linuxWorkersEnabled = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt; ListGeoRegionsWithHttpMessagesAsync(string sku, valuetype System.Nullable`1&lt;bool&gt; linuxWorkersEnabled, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync(System.String,System.Nullable{System.Boolean},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListGeoRegionsWithHttpMessagesAsync : string * Nullable&lt;bool&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListGeoRegionsWithHttpMessagesAsync (sku, linuxWorkersEnabled, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.GeoRegion&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sku" Type="System.String" />
        <Parameter Name="linuxWorkersEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sku">
            <span data-ttu-id="73fa2-140">Name der SKU, die zum Filtern der Regionen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="73fa2-140">Name of SKU used to filter the regions.</span></span> <span data-ttu-id="73fa2-141">Folgende Werte sind möglich: "Free", "Shared", "Basic", "Standard", "Premium", "PremiumV2", "Dynamic", "Isoliert"</span><span class="sxs-lookup"><span data-stu-id="73fa2-141">Possible values include: 'Free', 'Shared', 'Basic', 'Standard', 'Premium', 'PremiumV2', 'Dynamic', 'Isolated'</span></span>
            </param>
        <param name="linuxWorkersEnabled">
            <span data-ttu-id="73fa2-142">Geben Sie &lt;Code&gt;"true"&lt;/code&gt; ggf. nur Regionen zu filtern, die Linux-Worker-Unterstützung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-142">Specify &lt;code&gt;true&lt;/code&gt; if you want to filter to only regions that support Linux workers.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-143">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-143">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-145">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-145">Get a list of available geographical regions.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-146">Ruft eine Liste der verfügbaren geografischen Regionen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-146">Get a list of available geographical regions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListPremierAddOnOffersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="73fa2-147">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="73fa2-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-148">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-148">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-150">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="73fa2-150">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-151">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="73fa2-151">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListPremierAddOnOffersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt; ListPremierAddOnOffersWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListPremierAddOnOffersWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListPremierAddOnOffersWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.PremierAddOnOffer&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-152">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-152">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-154">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="73fa2-154">List all premier add-on offers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-155">Listen Sie aller premier-Add-Angebote auf.</span><span class="sxs-lookup"><span data-stu-id="73fa2-155">List all premier add-on offers.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSkusWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt; ListSkusWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSkusWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSkusWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;" Usage="iWebSiteManagementClient.ListSkusWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SkuInfos&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-156">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-156">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-157">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-157">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-158">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="73fa2-158">List all SKUs.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-159">Listen Sie alle SKUs.</span><span class="sxs-lookup"><span data-stu-id="73fa2-159">List all SKUs.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListSourceControlsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="73fa2-160">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="73fa2-160">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-161">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-161">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-163">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="73fa2-163">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-164">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="73fa2-164">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSourceControlsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt; ListSourceControlsWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSourceControlsWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;" Usage="iWebSiteManagementClient.ListSourceControlsWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-165">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-165">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-167">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="73fa2-167">Gets the source controls available for Azure websites.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-168">Ruft die verfügbaren Datenquellen-Steuerelementen für Azure-Websites.</span><span class="sxs-lookup"><span data-stu-id="73fa2-168">Gets the source controls available for Azure websites.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-169">Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="73fa2-169">Gets or sets the retry timeout in seconds for Long Running Operations.</span></span> <span data-ttu-id="73fa2-170">Standardwert ist 30.</span><span class="sxs-lookup"><span data-stu-id="73fa2-170">Default value is 30.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; MoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.MoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebSiteManagementClient.MoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="73fa2-171">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="73fa2-171">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="73fa2-172">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="73fa2-172">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-173">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-173">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-175">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-175">Move resources between resource groups.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-176">Verschieben von Ressourcen zwischen Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-176">Move resources between resource groups.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IProviderOperations Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IProviderOperations Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IProviderOperations" />
      <MemberSignature Language="F#" Value="member this.Provider : Microsoft.Azure.Management.WebSites.IProviderOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IProviderOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-177">Ruft die IProviderOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-177">Gets the IProviderOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Recommendations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IRecommendationsOperations Recommendations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Recommendations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Recommendations As IRecommendationsOperations" />
      <MemberSignature Language="F#" Value="member this.Recommendations : Microsoft.Azure.Management.WebSites.IRecommendationsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.Recommendations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IRecommendationsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-178">Ruft die IRecommendationsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-178">Gets the IRecommendationsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-179">Ermittelt oder Json-Serialisierungseinstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="73fa2-179">Gets or sets json serialization settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-180">Ihre Azure-Abonnement-ID.</span><span class="sxs-lookup"><span data-stu-id="73fa2-180">Your Azure subscription ID.</span></span> <span data-ttu-id="73fa2-181">Dies ist eine Zeichenfolge im GUID-Format (z. B. "00000000-0000-0000-0000-000000000000").</span><span class="sxs-lookup"><span data-stu-id="73fa2-181">This is a GUID-formatted string (e.g. 00000000-0000-0000-0000-000000000000).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TopLevelDomains">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations TopLevelDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.TopLevelDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TopLevelDomains As ITopLevelDomainsOperations" />
      <MemberSignature Language="F#" Value="member this.TopLevelDomains : Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.TopLevelDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.ITopLevelDomainsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-182">Ruft die ITopLevelDomainsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-182">Gets the ITopLevelDomainsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdatePublishingUserWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.User userDetails, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.User&gt;&gt; UpdatePublishingUserWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.User userDetails, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.User,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdatePublishingUserWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.User * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;" Usage="iWebSiteManagementClient.UpdatePublishingUserWithHttpMessagesAsync (userDetails, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.User&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userDetails" Type="Microsoft.Azure.Management.WebSites.Models.User" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="userDetails">
            <span data-ttu-id="73fa2-183">Details des Benutzers veröffentlichen</span><span class="sxs-lookup"><span data-stu-id="73fa2-183">Details of publishing user</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-184">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-184">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-186">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="73fa2-186">Updates publishing user</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-187">Updates, die publishing Benutzer</span><span class="sxs-lookup"><span data-stu-id="73fa2-187">Updates publishing user</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSourceControlWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync (string sourceControlType, Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt; UpdateSourceControlWithHttpMessagesAsync(string sourceControlType, class Microsoft.Azure.Management.WebSites.Models.SourceControl requestMessage, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.SourceControl,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSourceControlWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.SourceControl * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;" Usage="iWebSiteManagementClient.UpdateSourceControlWithHttpMessagesAsync (sourceControlType, requestMessage, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.SourceControl&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceControlType" Type="System.String" />
        <Parameter Name="requestMessage" Type="Microsoft.Azure.Management.WebSites.Models.SourceControl" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceControlType">
            <span data-ttu-id="73fa2-188">Typ des Datenquellen-Steuerelements</span><span class="sxs-lookup"><span data-stu-id="73fa2-188">Type of source control</span></span>
            </param>
        <param name="requestMessage">
            <span data-ttu-id="73fa2-189">Token Quellinformationen für Steuerelement</span><span class="sxs-lookup"><span data-stu-id="73fa2-189">Source control token information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-190">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-190">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-192">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="73fa2-192">Updates source control token</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-193">Updates Source Control token</span><span class="sxs-lookup"><span data-stu-id="73fa2-193">Updates source control token</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; ValidateMoveWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope moveResourceEnvelope, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateMoveWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateMoveWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="iWebSiteManagementClient.ValidateMoveWithHttpMessagesAsync (resourceGroupName, moveResourceEnvelope, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="moveResourceEnvelope" Type="Microsoft.Azure.Management.WebSites.Models.CsmMoveResourceEnvelope" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="73fa2-194">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="73fa2-194">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="moveResourceEnvelope">
            <span data-ttu-id="73fa2-195">Objekt, das Verschieben die Ressource darstellt.</span><span class="sxs-lookup"><span data-stu-id="73fa2-195">Object that represents the resource to move.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-196">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-196">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-198">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="73fa2-198">Validate whether a resource can be moved.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-199">Überprüfen Sie, ob eine Ressource verschoben werden kann.</span><span class="sxs-lookup"><span data-stu-id="73fa2-199">Validate whether a resource can be moved.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync (string resourceGroupName, Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt; ValidateWithHttpMessagesAsync(string resourceGroupName, class Microsoft.Azure.Management.WebSites.Models.ValidateRequest validateRequest, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.ValidateWithHttpMessagesAsync(System.String,Microsoft.Azure.Management.WebSites.Models.ValidateRequest,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateWithHttpMessagesAsync : string * Microsoft.Azure.Management.WebSites.Models.ValidateRequest * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;" Usage="iWebSiteManagementClient.ValidateWithHttpMessagesAsync (resourceGroupName, validateRequest, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.ValidateResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="validateRequest" Type="Microsoft.Azure.Management.WebSites.Models.ValidateRequest" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="73fa2-200">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="73fa2-200">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="validateRequest">
            <span data-ttu-id="73fa2-201">Fordern Sie hinsichtlich der Ressourcen, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="73fa2-201">Request with the resources to validate.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-202">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-202">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-204">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="73fa2-204">Validate if a resource can be created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-205">Überprüfen Sie, ob eine Ressource erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="73fa2-205">Validate if a resource can be created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyHostingEnvironmentVnetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync (Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt; VerifyHostingEnvironmentVnetWithHttpMessagesAsync(class Microsoft.Azure.Management.WebSites.Models.VnetParameters parameters, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync(Microsoft.Azure.Management.WebSites.Models.VnetParameters,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyHostingEnvironmentVnetWithHttpMessagesAsync : Microsoft.Azure.Management.WebSites.Models.VnetParameters * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;" Usage="iWebSiteManagementClient.VerifyHostingEnvironmentVnetWithHttpMessagesAsync (parameters, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.WebSites.Models.VnetValidationFailureDetails&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.WebSites.Models.VnetParameters" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="73fa2-206">VNET-Informationen</span><span class="sxs-lookup"><span data-stu-id="73fa2-206">VNET information</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="73fa2-207">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="73fa2-207">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="73fa2-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="73fa2-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="73fa2-209">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="73fa2-209">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="73fa2-210">Überprüft, ob dieses VNET mit einer App Service-Umgebung kompatibel ist, durch die Analyse der Netzwerksicherheitsgruppe-Regeln.</span><span class="sxs-lookup"><span data-stu-id="73fa2-210">Verifies if this VNET is compatible with an App Service Environment by analyzing the Network Security Group rules.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WebApps">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.IWebAppsOperations WebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.WebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebApps As IWebAppsOperations" />
      <MemberSignature Language="F#" Value="member this.WebApps : Microsoft.Azure.Management.WebSites.IWebAppsOperations" Usage="Microsoft.Azure.Management.WebSites.IWebSiteManagementClient.WebApps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.IWebAppsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73fa2-211">Ruft die IWebAppsOperations ab.</span><span class="sxs-lookup"><span data-stu-id="73fa2-211">Gets the IWebAppsOperations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>