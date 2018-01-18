<Type Name="DeletedSiteInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner">
  <TypeSignature Language="C#" Value="public class DeletedSiteInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DeletedSiteInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner" />
  <TypeSignature Language="VB.NET" Value="Public Class DeletedSiteInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DeletedSiteInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f2280-101">Eine gelöschte app.</span><span class="sxs-lookup"><span data-stu-id="f2280-101">A deleted app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSiteInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2280-102">Initialisiert eine neue Instanz der DeletedSiteInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f2280-102">Initializes a new instance of the DeletedSiteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSiteInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;DateTime&gt; deletedTimestamp = null, string state = null, System.Collections.Generic.IList&lt;string&gt; hostNames = null, string repositorySiteName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState = null, Nullable&lt;bool&gt; enabled = null, System.Collections.Generic.IList&lt;string&gt; enabledHostNames = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates = null, string serverFarmId = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;DateTime&gt; lastModifiedTimeUtc = null, Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig = null, System.Collections.Generic.IList&lt;string&gt; trafficManagerHostNames = null, Nullable&lt;bool&gt; premiumAppDeployed = null, Nullable&lt;bool&gt; scmSiteAlsoStopped = null, string targetSwapSlot = null, Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, string microService = null, string gatewaySiteName = null, Nullable&lt;bool&gt; clientAffinityEnabled = null, Nullable&lt;bool&gt; clientCertEnabled = null, Nullable&lt;bool&gt; hostNamesDisabled = null, string outboundIpAddresses = null, Nullable&lt;int&gt; containerSize = null, Nullable&lt;int&gt; dailyMemoryTimeQuota = null, Nullable&lt;DateTime&gt; suspendedTill = null, Nullable&lt;int&gt; maxNumberOfWorkers = null, Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo = null, string resourceGroup = null, Nullable&lt;bool&gt; isDefaultContainer = null, string defaultHostName = null, Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; deletedTimestamp, string state, class System.Collections.Generic.IList`1&lt;string&gt; hostNames, string repositorySiteName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; usageState, valuetype System.Nullable`1&lt;bool&gt; enabled, class System.Collections.Generic.IList`1&lt;string&gt; enabledHostNames, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; availabilityState, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; hostNameSslStates, string serverFarmId, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTimeUtc, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig siteConfig, class System.Collections.Generic.IList`1&lt;string&gt; trafficManagerHostNames, valuetype System.Nullable`1&lt;bool&gt; premiumAppDeployed, valuetype System.Nullable`1&lt;bool&gt; scmSiteAlsoStopped, string targetSwapSlot, class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile hostingEnvironmentProfile, string microService, string gatewaySiteName, valuetype System.Nullable`1&lt;bool&gt; clientAffinityEnabled, valuetype System.Nullable`1&lt;bool&gt; clientCertEnabled, valuetype System.Nullable`1&lt;bool&gt; hostNamesDisabled, string outboundIpAddresses, valuetype System.Nullable`1&lt;int32&gt; containerSize, valuetype System.Nullable`1&lt;int32&gt; dailyMemoryTimeQuota, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; suspendedTill, valuetype System.Nullable`1&lt;int32&gt; maxNumberOfWorkers, class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo cloningInfo, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; isDefaultContainer, string defaultHostName, class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus slotSwapStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{System.String},System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.UsageState},System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState},System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState},System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner (location, id, name, type, tags, deletedTimestamp, state, hostNames, repositorySiteName, usageState, enabled, enabledHostNames, availabilityState, hostNameSslStates, serverFarmId, reserved, lastModifiedTimeUtc, siteConfig, trafficManagerHostNames, premiumAppDeployed, scmSiteAlsoStopped, targetSwapSlot, hostingEnvironmentProfile, microService, gatewaySiteName, clientAffinityEnabled, clientCertEnabled, hostNamesDisabled, outboundIpAddresses, containerSize, dailyMemoryTimeQuota, suspendedTill, maxNumberOfWorkers, cloningInfo, resourceGroup, isDefaultContainer, defaultHostName, slotSwapStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="deletedTimestamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="hostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="repositorySiteName" Type="System.String" />
        <Parameter Name="usageState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="availabilityState" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" />
        <Parameter Name="hostNameSslStates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;" />
        <Parameter Name="serverFarmId" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastModifiedTimeUtc" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="siteConfig" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig" />
        <Parameter Name="trafficManagerHostNames" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="premiumAppDeployed" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="scmSiteAlsoStopped" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetSwapSlot" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile" />
        <Parameter Name="microService" Type="System.String" />
        <Parameter Name="gatewaySiteName" Type="System.String" />
        <Parameter Name="clientAffinityEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clientCertEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="hostNamesDisabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="outboundIpAddresses" Type="System.String" />
        <Parameter Name="containerSize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dailyMemoryTimeQuota" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="suspendedTill" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="maxNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cloningInfo" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="isDefaultContainer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="defaultHostName" Type="System.String" />
        <Parameter Name="slotSwapStatus" Type="Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="deletedTimestamp"><span data-ttu-id="f2280-103">Zeit in UTC, wann die app gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-103">Time in UTC when the app was deleted.</span></span></param>
        <param name="state"><span data-ttu-id="f2280-104">Aktuellen Status der app.</span><span class="sxs-lookup"><span data-stu-id="f2280-104">Current state of the app.</span></span></param>
        <param name="hostNames"><span data-ttu-id="f2280-105">Die Hostnamen der app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="f2280-105">Hostnames associated with the app.</span></span></param>
        <param name="repositorySiteName"><span data-ttu-id="f2280-106">Name der Repository-Website.</span><span class="sxs-lookup"><span data-stu-id="f2280-106">Name of the repository site.</span></span></param>
        <param name="usageState"><span data-ttu-id="f2280-107">Status, der angibt, ob die app die quotenauslastung überschritten hat.</span><span class="sxs-lookup"><span data-stu-id="f2280-107">State indicating whether the app has exceeded its quota usage.</span></span> <span data-ttu-id="f2280-108">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-108">Read-only.</span></span> <span data-ttu-id="f2280-109">Folgende Werte sind möglich: 'Normal', "Wurde überschritten"</span><span class="sxs-lookup"><span data-stu-id="f2280-109">Possible values include: 'Normal', 'Exceeded'</span></span></param>
        <param name="enabled"><span data-ttu-id="f2280-110">&lt;Code&gt;"true"&lt;/code&gt; ist die app aktiviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-110">&lt;code&gt;true&lt;/code&gt; if the app is enabled; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="f2280-111">Wenn dieser Wert auf "false" wird die app (die app offline geschaltet) deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="f2280-111">Setting this value to false disables the app (takes the app offline).</span></span></param>
        <param name="enabledHostNames"><span data-ttu-id="f2280-112">Aktivierte Hostnamen für die app. Hostnamen müssen zugewiesen werden (Siehe Hostnamen) und aktiviert.</span><span class="sxs-lookup"><span data-stu-id="f2280-112">Enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span>
            <span data-ttu-id="f2280-113">Andernfalls wird die app nicht auf diesen Hostnamen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="f2280-113">Otherwise, the app is not served on those hostnames.</span></span></param>
        <param name="availabilityState"><span data-ttu-id="f2280-114">Management Informationen den Verfügbarkeitsstatus für die app.</span><span class="sxs-lookup"><span data-stu-id="f2280-114">Management information availability state for the app.</span></span> <span data-ttu-id="f2280-115">Folgende Werte sind möglich: 'Normal', "Limited", "DisasterRecoveryMode"</span><span class="sxs-lookup"><span data-stu-id="f2280-115">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span></param>
        <param name="hostNameSslStates"><span data-ttu-id="f2280-116">Hostname-SSL-Status werden verwendet, um die SSL-Bindungen für app Hostnamen verwalten.</span><span class="sxs-lookup"><span data-stu-id="f2280-116">Hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span></param>
        <param name="serverFarmId"><span data-ttu-id="f2280-117">Ressourcen-ID des zugeordneten App Service-Plans formatiert: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span><span class="sxs-lookup"><span data-stu-id="f2280-117">Resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span></param>
        <param name="reserved"><span data-ttu-id="f2280-118">&lt;Code&gt;"true"&lt;/code&gt; Wenn reserviert ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-118">&lt;code&gt;true&lt;/code&gt; if reserved; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="lastModifiedTimeUtc"><span data-ttu-id="f2280-119">Letzte Änderung die app, in UTC angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-119">Last time the app was modified, in UTC.</span></span> <span data-ttu-id="f2280-120">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-120">Read-only.</span></span></param>
        <param name="siteConfig"><span data-ttu-id="f2280-121">Konfiguration der app.</span><span class="sxs-lookup"><span data-stu-id="f2280-121">Configuration of the app.</span></span></param>
        <param name="trafficManagerHostNames"><span data-ttu-id="f2280-122">Azure Traffic Manager Hostnamen, die der app zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="f2280-122">Azure Traffic Manager hostnames associated with the app.</span></span> <span data-ttu-id="f2280-123">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-123">Read-only.</span></span></param>
        <param name="premiumAppDeployed"><span data-ttu-id="f2280-124">Gibt an, ob die app als Premium-app bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-124">Indicates whether app is deployed as a premium app.</span></span></param>
        <param name="scmSiteAlsoStopped"><span data-ttu-id="f2280-125">&lt;Code&gt;"true"&lt;/code&gt; SCM (KUDU) Website beenden, wenn die app beendet ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-125">&lt;code&gt;true&lt;/code&gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="f2280-126">Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-126">The default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="targetSwapSlot"><span data-ttu-id="f2280-127">Gibt an, welche bereitstellungsslot in dieser app auslagern.</span><span class="sxs-lookup"><span data-stu-id="f2280-127">Specifies which deployment slot this app will swap into.</span></span> <span data-ttu-id="f2280-128">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-128">Read-only.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="f2280-129">App Service-Umgebung für die app zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="f2280-129">App Service Environment to use for the app.</span></span></param>
        <param name="microService"><span data-ttu-id="f2280-130">Micro-Dienste wie z. B. apps, die Logik-apps.</span><span class="sxs-lookup"><span data-stu-id="f2280-130">Micro services like apps, logic apps.</span></span></param>
        <param name="gatewaySiteName"><span data-ttu-id="f2280-131">Name des Gateway-app, die der app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="f2280-131">Name of gateway app associated with the app.</span></span></param>
        <param name="clientAffinityEnabled"><span data-ttu-id="f2280-132">&lt;Code&gt;"true"&lt;/code&gt; So aktivieren Sie die Clientaffinität; &lt;Code&gt;"false"&lt;/code&gt; senden Session Affinity Cookies Weiterleiten von Clientanforderungen in derselben Sitzung an dieselbe Instanz beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2280-132">&lt;code&gt;true&lt;/code&gt; to enable client affinity; &lt;code&gt;false&lt;/code&gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="f2280-133">Standardmäßig wird &lt;Code&gt;"true"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-133">Default is &lt;code&gt;true&lt;/code&gt;.</span></span></param>
        <param name="clientCertEnabled"><span data-ttu-id="f2280-134">&lt;Code&gt;"true"&lt;/code&gt; So aktivieren Sie die Clientzertifikatauthentifizierung (TLS gegenseitige Authentifizierung); andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-134">&lt;code&gt;true&lt;/code&gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="f2280-135">Standardmäßig wird &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-135">Default is &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="hostNamesDisabled"><span data-ttu-id="f2280-136">&lt;Code&gt;"true"&lt;/code&gt; So deaktivieren Sie den öffentlichen Hostnamen der app; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-136">&lt;code&gt;true&lt;/code&gt; to disable the public hostnames of the app; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span>
            <span data-ttu-id="f2280-137">Wenn &lt;Code&gt;"true"&lt;/code&gt;, die app ist nur über API Management-Prozesses zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f2280-137">If &lt;code&gt;true&lt;/code&gt;, the app is only accessible via API management process.</span></span></param>
        <param name="outboundIpAddresses"><span data-ttu-id="f2280-138">Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet.</span><span class="sxs-lookup"><span data-stu-id="f2280-138">List of IP addresses that the app uses for outbound connections (e.g. database access).</span></span>
            <span data-ttu-id="f2280-139">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-139">Read-only.</span></span></param>
        <param name="containerSize"><span data-ttu-id="f2280-140">Die Größe des Containers Funktion.</span><span class="sxs-lookup"><span data-stu-id="f2280-140">Size of the function container.</span></span></param>
        <param name="dailyMemoryTimeQuota"><span data-ttu-id="f2280-141">Maximal zulässige Arbeitsspeicher-Time-tageskontingent (gilt für nur dynamische apps).</span><span class="sxs-lookup"><span data-stu-id="f2280-141">Maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span></param>
        <param name="suspendedTill"><span data-ttu-id="f2280-142">App bis zum angehalten wird, für den Fall, dass Arbeitsspeicher Laufzeit überschritten wird.</span><span class="sxs-lookup"><span data-stu-id="f2280-142">App suspended till in case memory-time quota is exceeded.</span></span></param>
        <param name="maxNumberOfWorkers"><span data-ttu-id="f2280-143">Maximale Anzahl von Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="f2280-143">Maximum number of workers.</span></span>
            <span data-ttu-id="f2280-144">Dies gilt nur für Funktionen Container.</span><span class="sxs-lookup"><span data-stu-id="f2280-144">This only applies to Functions container.</span></span></param>
        <param name="cloningInfo"><span data-ttu-id="f2280-145">Wenn während der Erstellung der app angegeben, wird die app aus einer Quelle-app geklont.</span><span class="sxs-lookup"><span data-stu-id="f2280-145">If specified during app creation, the app is cloned from a source app.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="f2280-146">Name der Ressourcengruppe, die app gehört.</span><span class="sxs-lookup"><span data-stu-id="f2280-146">Name of the resource group the app belongs to.</span></span> <span data-ttu-id="f2280-147">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-147">Read-only.</span></span></param>
        <param name="isDefaultContainer"><span data-ttu-id="f2280-148">&lt;Code&gt;"true"&lt;/code&gt; ist die app einen Standardcontainer; andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-148">&lt;code&gt;true&lt;/code&gt; if the app is a default container; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="defaultHostName"><span data-ttu-id="f2280-149">Standard-Hostname der app.</span><span class="sxs-lookup"><span data-stu-id="f2280-149">Default hostname of the app.</span></span>
            <span data-ttu-id="f2280-150">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-150">Read-only.</span></span></param>
        <param name="slotSwapStatus"><span data-ttu-id="f2280-151">Status der letzten Bereitstellung Slot Swap-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f2280-151">Status of the last deployment slot swap operation.</span></span></param>
        <summary>
            <span data-ttu-id="f2280-152">Initialisiert eine neue Instanz der DeletedSiteInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f2280-152">Initializes a new instance of the DeletedSiteInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt; AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As Nullable(Of SiteAvailabilityState)" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availabilityState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-153">Ruft den Verfügbarkeitsstatus für Management-Informationen für die app ab.</span><span class="sxs-lookup"><span data-stu-id="f2280-153">Gets management information availability state for the app.</span></span>
            <span data-ttu-id="f2280-154">Folgende Werte sind möglich: 'Normal', "Limited", "DisasterRecoveryMode"</span><span class="sxs-lookup"><span data-stu-id="f2280-154">Possible values include: 'Normal', 'Limited', 'DisasterRecoveryMode'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientAffinityEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientAffinityEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientAffinityEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientAffinityEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-155">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So aktivieren Sie die Clientaffinität; &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; Senden Session Affinity Cookies Weiterleiten von Clientanforderungen in derselben Sitzung an dieselbe Instanz beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2280-155">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client affinity; &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt; to stop sending session affinity cookies, which route client requests in the same session to the same instance.</span></span> <span data-ttu-id="f2280-156">Standardmäßig wird &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-156">Default is &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ClientCertEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ClientCertEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-157">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; So aktivieren Sie die Clientzertifikatauthentifizierung (TLS gegenseitige Authentifizierung); andernfalls &amp;Lt; Code&amp;Gt; "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-157">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to enable client certificate authentication (TLS mutual authentication); otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="f2280-158">Standardmäßig wird &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-158">Default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cloningInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-159">Ruft ab oder legt fest, ob der angegebene während der Erstellung der app, die app aus einer Quelle-app geklont.</span><span class="sxs-lookup"><span data-stu-id="f2280-159">Gets or sets if specified during app creation, the app is cloned from a source app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ContainerSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSize As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-160">Ruft ab oder legt die Größe des Containers Funktion fest.</span><span class="sxs-lookup"><span data-stu-id="f2280-160">Gets or sets size of the function container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DailyMemoryTimeQuota">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DailyMemoryTimeQuota { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DailyMemoryTimeQuota" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DailyMemoryTimeQuota" />
      <MemberSignature Language="VB.NET" Value="Public Property DailyMemoryTimeQuota As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DailyMemoryTimeQuota : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DailyMemoryTimeQuota" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dailyMemoryTimeQuota")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-161">Ruft ab oder legt ihn fest maximale tageskontingent Arbeitsspeicher-Time (gilt für nur dynamische apps) zulässig.</span><span class="sxs-lookup"><span data-stu-id="f2280-161">Gets or sets maximum allowed daily memory-time quota (applicable on dynamic apps only).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-162">Ruft die Standard-Hostname der app.</span><span class="sxs-lookup"><span data-stu-id="f2280-162">Gets default hostname of the app.</span></span> <span data-ttu-id="f2280-163">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-163">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeletedTimestamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DeletedTimestamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DeletedTimestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DeletedTimestamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeletedTimestamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DeletedTimestamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.DeletedTimestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deletedTimestamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-164">Ruft Uhrzeit (UTC) ab, wenn die app gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-164">Gets time in UTC when the app was deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-165">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app, aktiviert ist, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-165">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is enabled; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="f2280-166">Wenn dieser Wert auf "false" wird die app (die app offline geschaltet) deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="f2280-166">Setting this value to false disables the app (takes the app offline).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enabledHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-167">Ruft das aktivierte Hostnamen für die app. Hostnamen müssen zugewiesen werden (Siehe Hostnamen) und aktiviert.</span><span class="sxs-lookup"><span data-stu-id="f2280-167">Gets enabled hostnames for the app.Hostnames need to be assigned (see HostNames) AND enabled.</span></span> <span data-ttu-id="f2280-168">Andernfalls wird die app nicht auf diesen Hostnamen verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="f2280-168">Otherwise, the app is not served on those hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewaySiteName">
      <MemberSignature Language="C#" Value="public string GatewaySiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewaySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.GatewaySiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewaySiteName As String" />
      <MemberSignature Language="F#" Value="member this.GatewaySiteName : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.GatewaySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewaySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-169">Ruft ab, oder legt ihn fest Name des Gateway-app, die der app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="f2280-169">Gets or sets name of gateway app associated with the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-170">Ruft ab, oder legt ihn fest app Service-Umgebung für die app zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="f2280-170">Gets or sets app Service Environment to use for the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-171">Ruft die Hostnamen der app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="f2280-171">Gets hostnames associated with the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; HostNamesDisabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNamesDisabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNamesDisabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNamesDisabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-172">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; deaktivieren Sie den öffentlichen Hostnamen der app; andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp; Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-172">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to disable the public hostnames of the app; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            <span data-ttu-id="f2280-173">Wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; die app ist nur über API Management-Prozesses zugegriffen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f2280-173">If &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, the app is only accessible via API management process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameSslStates As IList(Of HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameSslStates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-174">Ruft ab oder legt ihn fest Hostname SSL Zustände werden verwendet, um die SSL-Bindungen für app Hostnamen verwalten.</span><span class="sxs-lookup"><span data-stu-id="f2280-174">Gets or sets hostname SSL states are used to manage the SSL bindings for app's hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.IsDefaultContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isDefaultContainer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-175">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die app eine standardentitätscontainer ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-175">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the app is a default container; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTimeUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.LastModifiedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTimeUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTimeUtc : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.LastModifiedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTimeUtc")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-176">Ruft die letzten, an die app in UTC geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-176">Gets last time the app was modified, in UTC.</span></span> <span data-ttu-id="f2280-177">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-177">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MaxNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MaxNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-178">Ruft die maximale Anzahl von Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="f2280-178">Gets maximum number of workers.</span></span>
            <span data-ttu-id="f2280-179">Dies gilt nur für Funktionen Container.</span><span class="sxs-lookup"><span data-stu-id="f2280-179">This only applies to Functions container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicroService">
      <MemberSignature Language="C#" Value="public string MicroService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicroService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MicroService" />
      <MemberSignature Language="VB.NET" Value="Public Property MicroService As String" />
      <MemberSignature Language="F#" Value="member this.MicroService : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.MicroService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-180">Ruft ab, oder legt ihn fest micro-Dienste wie apps Logik-apps.</span><span class="sxs-lookup"><span data-stu-id="f2280-180">Gets or sets micro services like apps, logic apps.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIpAddresses">
      <MemberSignature Language="C#" Value="public string OutboundIpAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutboundIpAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.OutboundIpAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIpAddresses As String" />
      <MemberSignature Language="F#" Value="member this.OutboundIpAddresses : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.OutboundIpAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundIpAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-181">Ruft die Liste der IP-Adressen, die die app für ausgehende Verbindungen (z. B. Datenbankzugriff) verwendet.</span><span class="sxs-lookup"><span data-stu-id="f2280-181">Gets list of IP addresses that the app uses for outbound connections (e.g. database access).</span></span> <span data-ttu-id="f2280-182">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-182">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PremiumAppDeployed">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PremiumAppDeployed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PremiumAppDeployed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.PremiumAppDeployed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PremiumAppDeployed As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PremiumAppDeployed : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.PremiumAppDeployed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.premiumAppDeployed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-183">Ruft gibt an, ob die app als Premium-app bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f2280-183">Gets indicates whether app is deployed as a premium app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.repositorySiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-184">Ruft den Namen der Repository-Website ab.</span><span class="sxs-lookup"><span data-stu-id="f2280-184">Gets name of the repository site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reserved")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-185">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn reserviert ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-185">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if reserved; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-186">Ruft die Namen der Ressourcengruppe, zu der die app gehört.</span><span class="sxs-lookup"><span data-stu-id="f2280-186">Gets name of the resource group the app belongs to.</span></span> <span data-ttu-id="f2280-187">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-187">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ScmSiteAlsoStopped { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public Property ScmSiteAlsoStopped As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ScmSiteAlsoStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scmSiteAlsoStopped")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-188">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; SCM (KUDU) Website beenden, wenn die app beendet ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-188">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; to stop SCM (KUDU) site when the app is stopped; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="f2280-189">Die Standardeinstellung ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="f2280-189">The default is &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerFarmId">
      <MemberSignature Language="C#" Value="public string ServerFarmId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServerFarmId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ServerFarmId" />
      <MemberSignature Language="VB.NET" Value="Public Property ServerFarmId As String" />
      <MemberSignature Language="F#" Value="member this.ServerFarmId : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.ServerFarmId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serverFarmId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-190">Ruft ab oder legt ihn fest des zugehörigen App Service-Plans, formatiert als Ressourcen-ID: "/ subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span><span class="sxs-lookup"><span data-stu-id="f2280-190">Gets or sets resource ID of the associated App Service plan, formatted as: "/subscriptions/{subscriptionID}/resourceGroups/{groupName}/providers/Microsoft.Web/serverfarms/{appServicePlanName}".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig SiteConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SiteConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteConfig As SiteConfig" />
      <MemberSignature Language="F#" Value="member this.SiteConfig : Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SiteConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-191">Ruft ab oder legt die Konfiguration der app fest.</span><span class="sxs-lookup"><span data-stu-id="f2280-191">Gets or sets configuration of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SlotSwapStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus SlotSwapStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SlotSwapStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SlotSwapStatus As SlotSwapStatus" />
      <MemberSignature Language="F#" Value="member this.SlotSwapStatus : Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SlotSwapStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.slotSwapStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SlotSwapStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-192">Ruft den Status der letzten Bereitstellung Slot Swap-Vorgang ab.</span><span class="sxs-lookup"><span data-stu-id="f2280-192">Gets status of the last deployment slot swap operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-193">Ruft den aktuellen Status der app ab.</span><span class="sxs-lookup"><span data-stu-id="f2280-193">Gets current state of the app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendedTill">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SuspendedTill { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SuspendedTill" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SuspendedTill" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SuspendedTill As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SuspendedTill : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.SuspendedTill" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspendedTill")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-194">Ruft die app, die bis zum angehalten wird, für den Fall, dass Arbeitsspeicher Laufzeit überschritten wird.</span><span class="sxs-lookup"><span data-stu-id="f2280-194">Gets app suspended till in case memory-time quota is exceeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetSwapSlot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-195">Ruft gibt an, welche bereitstellungsslot in dieser app auslagern.</span><span class="sxs-lookup"><span data-stu-id="f2280-195">Gets specifies which deployment slot this app will swap into.</span></span>
            <span data-ttu-id="f2280-196">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-196">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficManagerHostNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-197">Ruft die Azure Traffic Manager-Hostnamen der app zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="f2280-197">Gets azure Traffic Manager hostnames associated with the app.</span></span>
            <span data-ttu-id="f2280-198">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-198">Read-only.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt; UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As Nullable(Of UsageState)" />
      <MemberSignature Language="F#" Value="member this.UsageState : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.usageState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.UsageState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f2280-199">Ruft Zustand, der angibt, ob die app die quotenauslastung überschritten hat.</span><span class="sxs-lookup"><span data-stu-id="f2280-199">Gets state indicating whether the app has exceeded its quota usage.</span></span>
            <span data-ttu-id="f2280-200">Schreibgeschützt.</span><span class="sxs-lookup"><span data-stu-id="f2280-200">Read-only.</span></span> <span data-ttu-id="f2280-201">Folgende Werte sind möglich: 'Normal', "Wurde überschritten"</span><span class="sxs-lookup"><span data-stu-id="f2280-201">Possible values include: 'Normal', 'Exceeded'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.DeletedSiteInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="deletedSiteInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f2280-202">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f2280-202">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f2280-203">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f2280-203">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>