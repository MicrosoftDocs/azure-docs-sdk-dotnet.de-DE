<Type Name="AppServiceEnvironmentResource" FullName="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource">
  <TypeSignature Language="C#" Value="public class AppServiceEnvironmentResource : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceEnvironmentResource extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceEnvironmentResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServiceEnvironmentResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9feb2-101">App Service-Umgebung ARM-Ressource.</span><span class="sxs-lookup"><span data-stu-id="9feb2-101">App Service Environment ARM resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-102">Initialisiert eine neue Instanz der AppServiceEnvironmentResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9feb2-102">Initializes a new instance of the AppServiceEnvironmentResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceEnvironmentResource (string location, string appServiceEnvironmentResourceName, string appServiceEnvironmentResourceLocation, Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status = null, string vnetName = null, string vnetResourceGroupName = null, string vnetSubnetName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode = null, string multiSize = null, Nullable&lt;int&gt; multiRoleCount = null, Nullable&lt;int&gt; ipsslAddressCount = null, string databaseEdition = null, string databaseServiceObjective = null, Nullable&lt;int&gt; upgradeDomains = null, string subscriptionId = null, string dnsSuffix = null, string lastAction = null, string lastActionResult = null, string allowedMultiSizes = null, string allowedWorkerSizes = null, Nullable&lt;int&gt; maximumNumberOfMachines = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList = null, Nullable&lt;bool&gt; environmentIsHealthy = null, string environmentStatus = null, string resourceGroup = null, Nullable&lt;int&gt; frontEndScaleFactor = null, Nullable&lt;int&gt; defaultFrontEndScaleFactor = null, string apiManagementAccountId = null, Nullable&lt;bool&gt; suspended = null, Nullable&lt;bool&gt; dynamicCacheEnabled = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings = null, System.Collections.Generic.IList&lt;string&gt; userWhitelistedIpRanges = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string appServiceEnvironmentResourceName, string appServiceEnvironmentResourceLocation, class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile virtualNetwork, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; workerPools, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; status, string vnetName, string vnetResourceGroupName, string vnetSubnetName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; internalLoadBalancingMode, string multiSize, valuetype System.Nullable`1&lt;int32&gt; multiRoleCount, valuetype System.Nullable`1&lt;int32&gt; ipsslAddressCount, string databaseEdition, string databaseServiceObjective, valuetype System.Nullable`1&lt;int32&gt; upgradeDomains, string subscriptionId, string dnsSuffix, string lastAction, string lastActionResult, string allowedMultiSizes, string allowedWorkerSizes, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfMachines, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; vipMappings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; environmentCapacities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; networkAccessControlList, valuetype System.Nullable`1&lt;bool&gt; environmentIsHealthy, string environmentStatus, string resourceGroup, valuetype System.Nullable`1&lt;int32&gt; frontEndScaleFactor, valuetype System.Nullable`1&lt;int32&gt; defaultFrontEndScaleFactor, string apiManagementAccountId, valuetype System.Nullable`1&lt;bool&gt; suspended, valuetype System.Nullable`1&lt;bool&gt; dynamicCacheEnabled, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; clusterSettings, class System.Collections.Generic.IList`1&lt;string&gt; userWhitelistedIpRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.#ctor(System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.WorkerPool},System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.StampCapacity},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry},System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.NameValuePair},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, appServiceEnvironmentResourceName As String, appServiceEnvironmentResourceLocation As String, virtualNetwork As VirtualNetworkProfile, workerPools As IList(Of WorkerPool), Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of ProvisioningState) = null, Optional status As Nullable(Of HostingEnvironmentStatus) = null, Optional vnetName As String = null, Optional vnetResourceGroupName As String = null, Optional vnetSubnetName As String = null, Optional internalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode) = null, Optional multiSize As String = null, Optional multiRoleCount As Nullable(Of Integer) = null, Optional ipsslAddressCount As Nullable(Of Integer) = null, Optional databaseEdition As String = null, Optional databaseServiceObjective As String = null, Optional upgradeDomains As Nullable(Of Integer) = null, Optional subscriptionId As String = null, Optional dnsSuffix As String = null, Optional lastAction As String = null, Optional lastActionResult As String = null, Optional allowedMultiSizes As String = null, Optional allowedWorkerSizes As String = null, Optional maximumNumberOfMachines As Nullable(Of Integer) = null, Optional vipMappings As IList(Of VirtualIPMapping) = null, Optional environmentCapacities As IList(Of StampCapacity) = null, Optional networkAccessControlList As IList(Of NetworkAccessControlEntry) = null, Optional environmentIsHealthy As Nullable(Of Boolean) = null, Optional environmentStatus As String = null, Optional resourceGroup As String = null, Optional frontEndScaleFactor As Nullable(Of Integer) = null, Optional defaultFrontEndScaleFactor As Nullable(Of Integer) = null, Optional apiManagementAccountId As String = null, Optional suspended As Nullable(Of Boolean) = null, Optional dynamicCacheEnabled As Nullable(Of Boolean) = null, Optional clusterSettings As IList(Of NameValuePair) = null, Optional userWhitelistedIpRanges As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource : string * string * string * Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;int&gt; * string * string * string * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; * Nullable&lt;bool&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource (location, appServiceEnvironmentResourceName, appServiceEnvironmentResourceLocation, virtualNetwork, workerPools, id, name, kind, type, tags, provisioningState, status, vnetName, vnetResourceGroupName, vnetSubnetName, internalLoadBalancingMode, multiSize, multiRoleCount, ipsslAddressCount, databaseEdition, databaseServiceObjective, upgradeDomains, subscriptionId, dnsSuffix, lastAction, lastActionResult, allowedMultiSizes, allowedWorkerSizes, maximumNumberOfMachines, vipMappings, environmentCapacities, networkAccessControlList, environmentIsHealthy, environmentStatus, resourceGroup, frontEndScaleFactor, defaultFrontEndScaleFactor, apiManagementAccountId, suspended, dynamicCacheEnabled, clusterSettings, userWhitelistedIpRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="appServiceEnvironmentResourceName" Type="System.String" />
        <Parameter Name="appServiceEnvironmentResourceLocation" Type="System.String" />
        <Parameter Name="virtualNetwork" Type="Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile" />
        <Parameter Name="workerPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" />
        <Parameter Name="vnetName" Type="System.String" />
        <Parameter Name="vnetResourceGroupName" Type="System.String" />
        <Parameter Name="vnetSubnetName" Type="System.String" />
        <Parameter Name="internalLoadBalancingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;" />
        <Parameter Name="multiSize" Type="System.String" />
        <Parameter Name="multiRoleCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="ipsslAddressCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="databaseEdition" Type="System.String" />
        <Parameter Name="databaseServiceObjective" Type="System.String" />
        <Parameter Name="upgradeDomains" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="dnsSuffix" Type="System.String" />
        <Parameter Name="lastAction" Type="System.String" />
        <Parameter Name="lastActionResult" Type="System.String" />
        <Parameter Name="allowedMultiSizes" Type="System.String" />
        <Parameter Name="allowedWorkerSizes" Type="System.String" />
        <Parameter Name="maximumNumberOfMachines" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="vipMappings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" />
        <Parameter Name="environmentCapacities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" />
        <Parameter Name="networkAccessControlList" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;" />
        <Parameter Name="environmentIsHealthy" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="environmentStatus" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="frontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="defaultFrontEndScaleFactor" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="apiManagementAccountId" Type="System.String" />
        <Parameter Name="suspended" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dynamicCacheEnabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="clusterSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;" />
        <Parameter Name="userWhitelistedIpRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="9feb2-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="9feb2-103">Resource Location.</span></span></param>
        <param name="appServiceEnvironmentResourceName"><span data-ttu-id="9feb2-104">Name des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-104">Name of the App Service Environment.</span></span></param>
        <param name="appServiceEnvironmentResourceLocation"><span data-ttu-id="9feb2-105">Speicherort der App Service-Umgebung, z. B. "West US".</span><span class="sxs-lookup"><span data-stu-id="9feb2-105">Location of the App Service Environment, e.g. "West US".</span></span></param>
        <param name="virtualNetwork"><span data-ttu-id="9feb2-106">Beschreibung des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9feb2-106">Description of the Virtual Network.</span></span></param>
        <param name="workerPools"><span data-ttu-id="9feb2-107">Beschreibung des workerpools mit workergröße IDs, die VM-Größen und die Anzahl der Worker in den einzelnen Pools.</span><span class="sxs-lookup"><span data-stu-id="9feb2-107">Description of worker pools with worker size IDs, VM sizes, and number of workers in each pool.</span></span></param>
        <param name="id"><span data-ttu-id="9feb2-108">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="9feb2-108">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="9feb2-109">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="9feb2-109">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="9feb2-110">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9feb2-110">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="9feb2-111">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="9feb2-111">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="9feb2-112">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="9feb2-112">Resource tags.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="9feb2-113">Der Bereitstellungsstatus der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-113">Provisioning state of the App Service Environment.</span></span> <span data-ttu-id="9feb2-114">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-114">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <param name="status"><span data-ttu-id="9feb2-115">Aktuellen Status der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-115">Current status of the App Service Environment.</span></span>
            <span data-ttu-id="9feb2-116">Folgende Werte sind möglich: "Vorbereitet", "bereit", "Skalieren", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-116">Possible values include: 'Preparing', 'Ready', 'Scaling', 'Deleting'</span></span></param>
        <param name="vnetName"><span data-ttu-id="9feb2-117">Name des virtuellen Netzwerks für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-117">Name of the Virtual Network for the App Service Environment.</span></span></param>
        <param name="vnetResourceGroupName"><span data-ttu-id="9feb2-118">Die Ressourcengruppe des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9feb2-118">Resource group of the Virtual Network.</span></span></param>
        <param name="vnetSubnetName"><span data-ttu-id="9feb2-119">Subnetz des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9feb2-119">Subnet of the Virtual Network.</span></span></param>
        <param name="internalLoadBalancingMode"><span data-ttu-id="9feb2-120">Gibt an, welche Endpunkte intern im Virtuellenetzwerk für die App Service-Umgebung fungieren soll.</span><span class="sxs-lookup"><span data-stu-id="9feb2-120">Specifies which endpoints to serve internally in the Virtual Network for the App Service Environment.</span></span> <span data-ttu-id="9feb2-121">Folgende Werte sind möglich: 'None', 'Web', "Veröffentlichen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-121">Possible values include: 'None', 'Web', 'Publishing'</span></span></param>
        <param name="multiSize"><span data-ttu-id="9feb2-122">Front-End-VM-Größe, z. B. "Mittel", "Large".</span><span class="sxs-lookup"><span data-stu-id="9feb2-122">Front-end VM size, e.g. "Medium", "Large".</span></span></param>
        <param name="multiRoleCount"><span data-ttu-id="9feb2-123">Die Anzahl der Front-End-Instanzen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-123">Number of front-end instances.</span></span></param>
        <param name="ipsslAddressCount"><span data-ttu-id="9feb2-124">Anzahl der für die App Service-Umgebung reservierte IP SSL-Adressen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-124">Number of IP SSL addresses reserved for the App Service Environment.</span></span></param>
        <param name="databaseEdition"><span data-ttu-id="9feb2-125">Edition der Metadaten-Datenbank für die App Service-Umgebung, z. B. "Standard".</span><span class="sxs-lookup"><span data-stu-id="9feb2-125">Edition of the metadata database for the App Service Environment, e.g. "Standard".</span></span></param>
        <param name="databaseServiceObjective"><span data-ttu-id="9feb2-126">Service-Ziel, der die Metadaten-Datenbank für die App Service-Umgebung, z. B. "S0".</span><span class="sxs-lookup"><span data-stu-id="9feb2-126">Service objective of the metadata database for the App Service Environment, e.g. "S0".</span></span></param>
        <param name="upgradeDomains"><span data-ttu-id="9feb2-127">Die Anzahl der upgradedomänen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-127">Number of upgrade domains of the App Service Environment.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="9feb2-128">Abonnement von der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-128">Subscription of the App Service Environment.</span></span></param>
        <param name="dnsSuffix"><span data-ttu-id="9feb2-129">DNS-Suffix des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-129">DNS suffix of the App Service Environment.</span></span></param>
        <param name="lastAction"><span data-ttu-id="9feb2-130">Letzte Bereitstellungsaktion auf der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-130">Last deployment action on the App Service Environment.</span></span></param>
        <param name="lastActionResult"><span data-ttu-id="9feb2-131">Ergebnis der letzten Bereitstellungsaktion auf die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-131">Result of the last deployment action on the App Service Environment.</span></span></param>
        <param name="allowedMultiSizes"><span data-ttu-id="9feb2-132">Liste von durch Trennzeichen getrennten Zeichenfolgen, die beschreiben, welche VM-Größen für Front-End-zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9feb2-132">List of comma separated strings describing which VM sizes are allowed for front-ends.</span></span></param>
        <param name="allowedWorkerSizes"><span data-ttu-id="9feb2-133">Liste von durch Trennzeichen getrennten Zeichenfolgen, die beschreiben, welche VM-Größen für Worker zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9feb2-133">List of comma separated strings describing which VM sizes are allowed for workers.</span></span></param>
        <param name="maximumNumberOfMachines"><span data-ttu-id="9feb2-134">Maximale Anzahl von virtuellen Computern in der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-134">Maximum number of VMs in the App Service Environment.</span></span></param>
        <param name="vipMappings"><span data-ttu-id="9feb2-135">Beschreibung des IP-SSL-Zuordnung für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-135">Description of IP SSL mapping for the App Service Environment.</span></span></param>
        <param name="environmentCapacities"><span data-ttu-id="9feb2-136">Kapazitäten für aktuelle insgesamt, verwendeten und verfügbaren Arbeitsthreads.</span><span class="sxs-lookup"><span data-stu-id="9feb2-136">Current total, used, and available worker capacities.</span></span></param>
        <param name="networkAccessControlList"><span data-ttu-id="9feb2-137">Die Zugriffssteuerungsliste für die Steuerung des Datenverkehrs an die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-137">Access control list for controlling traffic to the App Service Environment.</span></span></param>
        <param name="environmentIsHealthy"><span data-ttu-id="9feb2-138">"True" / "false", der angibt, ob die App Service-Umgebung fehlerfrei ist.</span><span class="sxs-lookup"><span data-stu-id="9feb2-138">True/false indicating whether the App Service Environment is healthy.</span></span></param>
        <param name="environmentStatus"><span data-ttu-id="9feb2-139">Ausführliche Meldung zur mit Ergebnissen der letzten Überprüfung der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-139">Detailed message about with results of the last check of the App Service Environment.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="9feb2-140">Die Ressourcengruppe des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-140">Resource group of the App Service Environment.</span></span></param>
        <param name="frontEndScaleFactor"><span data-ttu-id="9feb2-141">Der Skalierungsfaktor für Front-Ends.</span><span class="sxs-lookup"><span data-stu-id="9feb2-141">Scale factor for front-ends.</span></span></param>
        <param name="defaultFrontEndScaleFactor"><span data-ttu-id="9feb2-142">Standard-Skalierungsfaktor für Front-Ends.</span><span class="sxs-lookup"><span data-stu-id="9feb2-142">Default Scale Factor for FrontEnds.</span></span></param>
        <param name="apiManagementAccountId"><span data-ttu-id="9feb2-143">Verwaltungskonto für API-App Service-Umgebung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9feb2-143">API Management Account associated with the App Service Environment.</span></span></param>
        <param name="suspended"><span data-ttu-id="9feb2-144">&lt;Code&gt;"true"&lt;/code&gt; ist der App Service-Umgebung angehalten wurde, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="9feb2-144">&lt;code&gt;true&lt;/code&gt; if the App Service Environment is suspended; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span> <span data-ttu-id="9feb2-145">Die Umgebung kann angehalten werden, z. B. wenn der verwaltungsendpunkt nicht mehr verfügbar ist (wahrscheinlich weil NSG den eingehenden Datenverkehr blockiert).</span><span class="sxs-lookup"><span data-stu-id="9feb2-145">The environment can be suspended, e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span></param>
        <param name="dynamicCacheEnabled"><span data-ttu-id="9feb2-146">"True" / "false" gibt an, ob die App Service-Umgebung angehalten wird.</span><span class="sxs-lookup"><span data-stu-id="9feb2-146">True/false indicating whether the App Service Environment is suspended.</span></span> <span data-ttu-id="9feb2-147">Die Umgebung kann angehalten, z. B. wenn der verwaltungsendpunkt nicht mehr verfügbar ist (wahrscheinlich weil NSG den eingehenden Datenverkehr blockiert).</span><span class="sxs-lookup"><span data-stu-id="9feb2-147">The environment can be suspended e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span></param>
        <param name="clusterSettings"><span data-ttu-id="9feb2-148">Benutzerdefinierte Einstellungen für das Verhalten der App Service-Umgebung ändern.</span><span class="sxs-lookup"><span data-stu-id="9feb2-148">Custom settings for changing the behavior of the App Service Environment.</span></span></param>
        <param name="userWhitelistedIpRanges"><span data-ttu-id="9feb2-149">Benutzer IP-Adressbereiche Blockierung auf ASE Db hinzugefügt</span><span class="sxs-lookup"><span data-stu-id="9feb2-149">User added ip ranges to whitelist on ASE db</span></span></param>
        <summary>
            <span data-ttu-id="9feb2-150">Initialisiert eine neue Instanz der AppServiceEnvironmentResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9feb2-150">Initializes a new instance of the AppServiceEnvironmentResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedMultiSizes">
      <MemberSignature Language="C#" Value="public string AllowedMultiSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedMultiSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AllowedMultiSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedMultiSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedMultiSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AllowedMultiSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedMultiSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-151">Ruft Liste mit durch Trennzeichen getrennten Zeichenfolgen beschreiben, welche VM-Größen für Front-End-zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9feb2-151">Gets list of comma separated strings describing which VM sizes are allowed for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedWorkerSizes">
      <MemberSignature Language="C#" Value="public string AllowedWorkerSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AllowedWorkerSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AllowedWorkerSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllowedWorkerSizes As String" />
      <MemberSignature Language="F#" Value="member this.AllowedWorkerSizes : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AllowedWorkerSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowedWorkerSizes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-152">Ruft Liste mit durch Trennzeichen getrennten Zeichenfolgen beschreiben, welche VM-Größen für Worker zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9feb2-152">Gets list of comma separated strings describing which VM sizes are allowed for workers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiManagementAccountId">
      <MemberSignature Language="C#" Value="public string ApiManagementAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiManagementAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ApiManagementAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property ApiManagementAccountId As String" />
      <MemberSignature Language="F#" Value="member this.ApiManagementAccountId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ApiManagementAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.apiManagementAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-153">Ruft ab, oder legt ihn fest Verwaltungskonto für API-App Service-Umgebung zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9feb2-153">Gets or sets API Management Account associated with the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironmentResourceLocation">
      <MemberSignature Language="C#" Value="public string AppServiceEnvironmentResourceLocation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServiceEnvironmentResourceLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AppServiceEnvironmentResourceLocation" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServiceEnvironmentResourceLocation As String" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironmentResourceLocation : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AppServiceEnvironmentResourceLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-154">Ruft ab oder legt die Position des App Service-Umgebung, z. B. "West US".</span><span class="sxs-lookup"><span data-stu-id="9feb2-154">Gets or sets location of the App Service Environment, e.g. "West US".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServiceEnvironmentResourceName">
      <MemberSignature Language="C#" Value="public string AppServiceEnvironmentResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServiceEnvironmentResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AppServiceEnvironmentResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServiceEnvironmentResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AppServiceEnvironmentResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.AppServiceEnvironmentResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-155">Ruft ab oder legt den Namen der App Service-Umgebung fest.</span><span class="sxs-lookup"><span data-stu-id="9feb2-155">Gets or sets name of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; ClusterSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ClusterSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterSettings As IList(Of NameValuePair)" />
      <MemberSignature Language="F#" Value="member this.ClusterSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ClusterSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NameValuePair&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-156">Ruft ab oder legt ihn fest benutzerdefinierte Einstellungen für das Verhalten der App Service-Umgebung ändern.</span><span class="sxs-lookup"><span data-stu-id="9feb2-156">Gets or sets custom settings for changing the behavior of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseEdition">
      <MemberSignature Language="C#" Value="public string DatabaseEdition { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseEdition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DatabaseEdition" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseEdition As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseEdition : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DatabaseEdition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseEdition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-157">Ruft die Metadaten-Datenbank-Edition für die App Service-Umgebung, z. B. "Standard".</span><span class="sxs-lookup"><span data-stu-id="9feb2-157">Gets edition of the metadata database for the App Service Environment, e.g. "Standard".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseServiceObjective">
      <MemberSignature Language="C#" Value="public string DatabaseServiceObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DatabaseServiceObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DatabaseServiceObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseServiceObjective As String" />
      <MemberSignature Language="F#" Value="member this.DatabaseServiceObjective : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DatabaseServiceObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseServiceObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-158">Ruft dienstziel der metadatendatenbank für die App Service-Umgebung, z. B. "S0".</span><span class="sxs-lookup"><span data-stu-id="9feb2-158">Gets service objective of the metadata database for the App Service Environment, e.g. "S0".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultFrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DefaultFrontEndScaleFactor { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DefaultFrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DefaultFrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultFrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DefaultFrontEndScaleFactor : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DefaultFrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultFrontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-159">Ruft standardmäßig Skalierungsfaktor für Front-Ends.</span><span class="sxs-lookup"><span data-stu-id="9feb2-159">Gets default Scale Factor for FrontEnds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSuffix">
      <MemberSignature Language="C#" Value="public string DnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.DnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DnsSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-160">Ruft ab oder legt die DNS-Suffix des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-160">Gets or sets DNS suffix of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCacheEnabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; DynamicCacheEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; DynamicCacheEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DynamicCacheEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCacheEnabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.DynamicCacheEnabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.DynamicCacheEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dynamicCacheEnabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-161">Ruft ab, oder legt ihn fest, der angibt, ob die App Service-Umgebung ausgesetzt ist wahr/falsch.</span><span class="sxs-lookup"><span data-stu-id="9feb2-161">Gets or sets true/false indicating whether the App Service Environment is suspended.</span></span> <span data-ttu-id="9feb2-162">Die Umgebung kann angehalten, z. B. wenn der verwaltungsendpunkt nicht mehr verfügbar ist (wahrscheinlich weil NSG den eingehenden Datenverkehr blockiert).</span><span class="sxs-lookup"><span data-stu-id="9feb2-162">The environment can be suspended e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentCapacities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt; EnvironmentCapacities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentCapacities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentCapacities As IList(Of StampCapacity)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentCapacities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentCapacities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentCapacities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.StampCapacity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-163">Ruft die aktuelle insgesamt, verwendeten und verfügbaren Arbeitsthreads Kapazitäten ab.</span><span class="sxs-lookup"><span data-stu-id="9feb2-163">Gets current total, used, and available worker capacities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentIsHealthy">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnvironmentIsHealthy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnvironmentIsHealthy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentIsHealthy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentIsHealthy As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentIsHealthy : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentIsHealthy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentIsHealthy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-164">Ruft ab, der angibt, ob die App Service-Umgebung fehlerfrei ist wahr/falsch.</span><span class="sxs-lookup"><span data-stu-id="9feb2-164">Gets true/false indicating whether the App Service Environment is healthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentStatus">
      <MemberSignature Language="C#" Value="public string EnvironmentStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EnvironmentStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnvironmentStatus As String" />
      <MemberSignature Language="F#" Value="member this.EnvironmentStatus : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.EnvironmentStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-165">Ruft ausführliche Meldung zur mit Ergebnissen der letzten Überprüfung der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-165">Gets detailed message about with results of the last check of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontEndScaleFactor">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; FrontEndScaleFactor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; FrontEndScaleFactor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.FrontEndScaleFactor" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontEndScaleFactor As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.FrontEndScaleFactor : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.FrontEndScaleFactor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontEndScaleFactor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-166">Abrufen oder Festlegen der Skalierungsfaktor für Front-Ends.</span><span class="sxs-lookup"><span data-stu-id="9feb2-166">Gets or sets scale factor for front-ends.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalLoadBalancingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; InternalLoadBalancingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.InternalLoadBalancingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalLoadBalancingMode As Nullable(Of InternalLoadBalancingMode)" />
      <MemberSignature Language="F#" Value="member this.InternalLoadBalancingMode : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.InternalLoadBalancingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.internalLoadBalancingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.InternalLoadBalancingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-167">Ruft ab oder legt gibt an, welche Endpunkte intern im Virtuellenetzwerk für die App Service-Umgebung fungieren soll.</span><span class="sxs-lookup"><span data-stu-id="9feb2-167">Gets or sets specifies which endpoints to serve internally in the Virtual Network for the App Service Environment.</span></span> <span data-ttu-id="9feb2-168">Folgende Werte sind möglich: 'None', 'Web', "Veröffentlichen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-168">Possible values include: 'None', 'Web', 'Publishing'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpsslAddressCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IpsslAddressCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IpsslAddressCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.IpsslAddressCount" />
      <MemberSignature Language="VB.NET" Value="Public Property IpsslAddressCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IpsslAddressCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.IpsslAddressCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipsslAddressCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-169">Ruft ab oder legt die Anzahl der für die App Service-Umgebung reservierte IP SSL-Adressen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-169">Gets or sets number of IP SSL addresses reserved for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAction">
      <MemberSignature Language="C#" Value="public string LastAction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastAction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.LastAction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAction As String" />
      <MemberSignature Language="F#" Value="member this.LastAction : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.LastAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastAction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-170">Ruft das letzte Bereitstellungsaktion auf der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-170">Gets last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastActionResult">
      <MemberSignature Language="C#" Value="public string LastActionResult { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastActionResult" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.LastActionResult" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastActionResult As String" />
      <MemberSignature Language="F#" Value="member this.LastActionResult : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.LastActionResult" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastActionResult")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-171">Ruft das Ergebnis der letzten Bereitstellungsaktion auf der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-171">Gets result of the last deployment action on the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfMachines">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MaximumNumberOfMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfMachines As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfMachines : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MaximumNumberOfMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfMachines")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-172">Ruft die maximale Anzahl von virtuellen Computern in der App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="9feb2-172">Gets maximum number of VMs in the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiRoleCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MultiRoleCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MultiRoleCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MultiRoleCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiRoleCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MultiRoleCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MultiRoleCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiRoleCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-173">Ruft ab oder legt die Anzahl der Front-End-Instanzen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-173">Gets or sets number of front-end instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiSize">
      <MemberSignature Language="C#" Value="public string MultiSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MultiSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MultiSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiSize As String" />
      <MemberSignature Language="F#" Value="member this.MultiSize : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.MultiSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.multiSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-174">Ruft ab oder legt Front-End-VM-Größe, z. B. "Mittel", "Large".</span><span class="sxs-lookup"><span data-stu-id="9feb2-174">Gets or sets front-end VM size, e.g. "Medium", "Large".</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkAccessControlList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; NetworkAccessControlList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.NetworkAccessControlList" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkAccessControlList As IList(Of NetworkAccessControlEntry)" />
      <MemberSignature Language="F#" Value="member this.NetworkAccessControlList : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.NetworkAccessControlList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAccessControlList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.NetworkAccessControlEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-175">Abrufen oder Festlegen der Zugriffssteuerungsliste für die Steuerung des Datenverkehrs an die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-175">Gets or sets access control list for controlling traffic to the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-176">Ruft die Status der App Service-Umgebung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-176">Gets provisioning state of the App Service Environment.</span></span> <span data-ttu-id="9feb2-177">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-177">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="9feb2-178">Ruft die Ressourcengruppe des App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="9feb2-178">Gets resource group of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of HostingEnvironmentStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-179">Ruft die aktuellen Status der App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="9feb2-179">Gets current status of the App Service Environment.</span></span> <span data-ttu-id="9feb2-180">Folgende Werte sind möglich: "Vorbereitet", "bereit", "Skalieren", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="9feb2-180">Possible values include: 'Preparing', 'Ready', 'Scaling', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-181">Ruft die Abonnement-App Service-Umgebung ab.</span><span class="sxs-lookup"><span data-stu-id="9feb2-181">Gets subscription of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspended">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Suspended { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Suspended" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.Suspended" />
      <MemberSignature Language="VB.NET" Value="Public Property Suspended As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Suspended : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.Suspended" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.suspended")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-182">Ruft ab oder legt ihn fest &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; Wenn die App Service-Umgebung, angehalten wurde, andernfalls ist &amp;Lt; Code&amp;Gt "false"&amp;Lt; /code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="9feb2-182">Gets or sets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if the App Service Environment is suspended; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span> <span data-ttu-id="9feb2-183">Die Umgebung kann angehalten werden, z. B. wenn der verwaltungsendpunkt nicht mehr verfügbar ist (wahrscheinlich weil NSG den eingehenden Datenverkehr blockiert).</span><span class="sxs-lookup"><span data-stu-id="9feb2-183">The environment can be suspended, e.g. when the management endpoint is no longer available (most likely because NSG blocked the incoming traffic).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeDomains")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-184">Ruft die Anzahl der upgradedomänen des App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-184">Gets number of upgrade domains of the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserWhitelistedIpRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; UserWhitelistedIpRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; UserWhitelistedIpRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.UserWhitelistedIpRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property UserWhitelistedIpRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.UserWhitelistedIpRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.UserWhitelistedIpRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userWhitelistedIpRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-185">Ruft ab oder legt ihn fest hinzugefügte Benutzer Ip-Adressbereiche Blockierung auf ASE-Db</span><span class="sxs-lookup"><span data-stu-id="9feb2-185">Gets or sets user added ip ranges to whitelist on ASE db</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServiceEnvironmentResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-186">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9feb2-186">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9feb2-187">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9feb2-187">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VipMappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt; VipMappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VipMappings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VipMappings As IList(Of VirtualIPMapping)" />
      <MemberSignature Language="F#" Value="member this.VipMappings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VipMappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vipMappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VirtualIPMapping&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-188">Ruft die Beschreibung von IP-SSL für die App Service-Umgebung zuordnen.</span><span class="sxs-lookup"><span data-stu-id="9feb2-188">Gets description of IP SSL mapping for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile VirtualNetwork" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VirtualNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetwork As VirtualNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.VirtualNetwork : Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VirtualNetwork" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetwork")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VirtualNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-189">Ruft ab oder legt die Beschreibung des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9feb2-189">Gets or sets description of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetName">
      <MemberSignature Language="C#" Value="public string VnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-190">Ruft ab oder legt Name des virtuellen Netzwerks für die App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="9feb2-190">Gets or sets name of the Virtual Network for the App Service Environment.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceGroupName">
      <MemberSignature Language="C#" Value="public string VnetResourceGroupName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceGroupName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetResourceGroupName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceGroupName As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceGroupName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetResourceGroupName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceGroupName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-191">Ruft ab, oder legt die Ressourcengruppe des virtuellen Netzwerks fest.</span><span class="sxs-lookup"><span data-stu-id="9feb2-191">Gets or sets resource group of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetSubnetName">
      <MemberSignature Language="C#" Value="public string VnetSubnetName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetSubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetSubnetName" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetSubnetName As String" />
      <MemberSignature Language="F#" Value="member this.VnetSubnetName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.VnetSubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetSubnetName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-192">Ruft ab, oder legt ihn fest Subnetz des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9feb2-192">Gets or sets subnet of the Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WorkerPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; WorkerPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.WorkerPools" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerPools As IList(Of WorkerPool)" />
      <MemberSignature Language="F#" Value="member this.WorkerPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServiceEnvironmentResource.WorkerPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.WorkerPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9feb2-193">Ruft ab oder legt Beschreibung des workerpools mit workergröße IDs, VM-Größen und Anzahl der Worker in den einzelnen Pools.</span><span class="sxs-lookup"><span data-stu-id="9feb2-193">Gets or sets description of worker pools with worker size IDs, VM sizes, and number of workers in each pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>