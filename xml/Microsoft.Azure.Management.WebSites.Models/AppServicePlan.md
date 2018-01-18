<Type Name="AppServicePlan" FullName="Microsoft.Azure.Management.WebSites.Models.AppServicePlan">
  <TypeSignature Language="C#" Value="public class AppServicePlan : Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServicePlan extends Microsoft.Azure.Management.WebSites.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AppServicePlan" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServicePlan&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type AppServicePlan = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="50fc7-101">App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="50fc7-101">App Service plan.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlan ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-102">Initialisiert eine neue Instanz der AppServicePlan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50fc7-102">Initializes a new instance of the AppServicePlan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServicePlan (string location, string id = null, string name = null, string kind = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string appServicePlanName = null, string workerTierName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status = null, string subscription = null, string adminSiteName = null, Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile = null, Nullable&lt;int&gt; maximumNumberOfWorkers = null, string geoRegion = null, Nullable&lt;bool&gt; perSiteScaling = null, Nullable&lt;int&gt; numberOfSites = null, Nullable&lt;bool&gt; isSpot = null, Nullable&lt;DateTime&gt; spotExpirationTime = null, string resourceGroup = null, Nullable&lt;bool&gt; reserved = null, Nullable&lt;int&gt; targetWorkerCount = null, Nullable&lt;int&gt; targetWorkerSizeId = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState = null, Microsoft.Azure.Management.WebSites.Models.SkuDescription sku = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string kind, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string appServicePlanName, string workerTierName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; status, string subscription, string adminSiteName, class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile hostingEnvironmentProfile, valuetype System.Nullable`1&lt;int32&gt; maximumNumberOfWorkers, string geoRegion, valuetype System.Nullable`1&lt;bool&gt; perSiteScaling, valuetype System.Nullable`1&lt;int32&gt; numberOfSites, valuetype System.Nullable`1&lt;bool&gt; isSpot, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; spotExpirationTime, string resourceGroup, valuetype System.Nullable`1&lt;bool&gt; reserved, valuetype System.Nullable`1&lt;int32&gt; targetWorkerCount, valuetype System.Nullable`1&lt;int32&gt; targetWorkerSizeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; provisioningState, class Microsoft.Azure.Management.WebSites.Models.SkuDescription sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.#ctor(System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.StatusOptions},System.String,System.String,Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile,System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.Nullable{System.Boolean},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.WebSites.Models.ProvisioningState},Microsoft.Azure.Management.WebSites.Models.SkuDescription)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AppServicePlan : string * string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; * string * string * Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; * Microsoft.Azure.Management.WebSites.Models.SkuDescription -&gt; Microsoft.Azure.Management.WebSites.Models.AppServicePlan" Usage="new Microsoft.Azure.Management.WebSites.Models.AppServicePlan (location, id, name, kind, type, tags, appServicePlanName, workerTierName, status, subscription, adminSiteName, hostingEnvironmentProfile, maximumNumberOfWorkers, geoRegion, perSiteScaling, numberOfSites, isSpot, spotExpirationTime, resourceGroup, reserved, targetWorkerCount, targetWorkerSizeId, provisioningState, sku)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="appServicePlanName" Type="System.String" />
        <Parameter Name="workerTierName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" />
        <Parameter Name="subscription" Type="System.String" />
        <Parameter Name="adminSiteName" Type="System.String" />
        <Parameter Name="hostingEnvironmentProfile" Type="Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile" />
        <Parameter Name="maximumNumberOfWorkers" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="geoRegion" Type="System.String" />
        <Parameter Name="perSiteScaling" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="numberOfSites" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSpot" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="spotExpirationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="reserved" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="targetWorkerCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="targetWorkerSizeId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="50fc7-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="50fc7-103">Resource Location.</span></span></param>
        <param name="id"><span data-ttu-id="50fc7-104">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="50fc7-104">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="50fc7-105">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="50fc7-105">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="50fc7-106">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="50fc7-106">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="50fc7-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="50fc7-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="50fc7-108">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="50fc7-108">Resource tags.</span></span></param>
        <param name="appServicePlanName"><span data-ttu-id="50fc7-109">Der Name für den App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="50fc7-109">Name for the App Service plan.</span></span></param>
        <param name="workerTierName"><span data-ttu-id="50fc7-110">Ziel-workerebene für die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="50fc7-110">Target worker tier assigned to the App Service plan.</span></span></param>
        <param name="status"><span data-ttu-id="50fc7-111">Status der App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="50fc7-111">App Service plan status.</span></span> <span data-ttu-id="50fc7-112">Folgende Werte sind möglich: "Bereit", "Ausstehend", "Erstellen"</span><span class="sxs-lookup"><span data-stu-id="50fc7-112">Possible values include: 'Ready', 'Pending', 'Creating'</span></span></param>
        <param name="subscription"><span data-ttu-id="50fc7-113">App Service-Plan-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="50fc7-113">App Service plan subscription.</span></span></param>
        <param name="adminSiteName"><span data-ttu-id="50fc7-114">Verwaltungsstandort App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="50fc7-114">App Service plan administration site.</span></span></param>
        <param name="hostingEnvironmentProfile"><span data-ttu-id="50fc7-115">Spezifikation für die App Service-Umgebung für die App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="50fc7-115">Specification for the App Service Environment to use for the App Service plan.</span></span></param>
        <param name="maximumNumberOfWorkers"><span data-ttu-id="50fc7-116">Maximale Anzahl von Instanzen, die dieser App Service-Plan zugewiesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="50fc7-116">Maximum number of instances that can be assigned to this App Service plan.</span></span></param>
        <param name="geoRegion"><span data-ttu-id="50fc7-117">Geografischer Standort für den App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="50fc7-117">Geographical location for the App Service plan.</span></span></param>
        <param name="perSiteScaling"><span data-ttu-id="50fc7-118">Wenn &lt;Code&gt;"true"&lt;/code&gt;, apps diese App Service-Plan zugewiesen können unabhängig voneinander skaliert werden.</span><span class="sxs-lookup"><span data-stu-id="50fc7-118">If &lt;code&gt;true&lt;/code&gt;, apps assigned to this App Service plan can be scaled independently.</span></span>
            <span data-ttu-id="50fc7-119">Wenn &lt;Code&gt;"false"&lt;/code&gt;, apps diese App Service-Plan zugewiesen werden für alle Instanzen des Plans skaliert.</span><span class="sxs-lookup"><span data-stu-id="50fc7-119">If &lt;code&gt;false&lt;/code&gt;, apps assigned to this App Service plan will scale to all instances of the plan.</span></span></param>
        <param name="numberOfSites"><span data-ttu-id="50fc7-120">Anzahl der apps diese App Service-Plan zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="50fc7-120">Number of apps assigned to this App Service plan.</span></span></param>
        <param name="isSpot"><span data-ttu-id="50fc7-121">Wenn &lt;Code&gt;"true"&lt;/code&gt;, diese App Service-Plan Volltonfarbe Instanzen besitzt.</span><span class="sxs-lookup"><span data-stu-id="50fc7-121">If &lt;code&gt;true&lt;/code&gt;, this App Service Plan owns spot instances.</span></span></param>
        <param name="spotExpirationTime"><span data-ttu-id="50fc7-122">Die Uhrzeit des Ablaufs die Serverfarm.</span><span class="sxs-lookup"><span data-stu-id="50fc7-122">The time when the server farm expires.</span></span> <span data-ttu-id="50fc7-123">Nur gültig, wenn es sich um eine Volltonfarbe Serverfarm ist.</span><span class="sxs-lookup"><span data-stu-id="50fc7-123">Valid only if it is a spot server farm.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="50fc7-124">Die Ressourcengruppe des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="50fc7-124">Resource group of the App Service plan.</span></span></param>
        <param name="reserved"><span data-ttu-id="50fc7-125">Reserviert.</span><span class="sxs-lookup"><span data-stu-id="50fc7-125">Reserved.</span></span></param>
        <param name="targetWorkerCount"><span data-ttu-id="50fc7-126">Skalieren von Worker-Anzahl.</span><span class="sxs-lookup"><span data-stu-id="50fc7-126">Scaling worker count.</span></span></param>
        <param name="targetWorkerSizeId"><span data-ttu-id="50fc7-127">Skalierung Worker Größe-ID.</span><span class="sxs-lookup"><span data-stu-id="50fc7-127">Scaling worker size ID.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="50fc7-128">Der Bereitstellungsstatus der App Service-Umgebung.</span><span class="sxs-lookup"><span data-stu-id="50fc7-128">Provisioning state of the App Service Environment.</span></span> <span data-ttu-id="50fc7-129">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="50fc7-129">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span></param>
        <param name="sku">To be added.</param>
        <summary>
            <span data-ttu-id="50fc7-130">Initialisiert eine neue Instanz der AppServicePlan-Klasse.</span><span class="sxs-lookup"><span data-stu-id="50fc7-130">Initializes a new instance of the AppServicePlan class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdminSiteName">
      <MemberSignature Language="C#" Value="public string AdminSiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdminSiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.AdminSiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property AdminSiteName As String" />
      <MemberSignature Language="F#" Value="member this.AdminSiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.AdminSiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.adminSiteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-131">Ruft ab, oder legt ihn fest app Service-Plan Verwaltungsstandort.</span><span class="sxs-lookup"><span data-stu-id="50fc7-131">Gets or sets app Service plan administration site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlanName">
      <MemberSignature Language="C#" Value="public string AppServicePlanName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlanName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.AppServicePlanName" />
      <MemberSignature Language="VB.NET" Value="Public Property AppServicePlanName As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlanName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.AppServicePlanName" />
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
            <span data-ttu-id="50fc7-132">Ruft ab, oder legt ihn fest Namen für den App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="50fc7-132">Gets or sets name for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoRegion">
      <MemberSignature Language="C#" Value="public string GeoRegion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GeoRegion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.GeoRegion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoRegion As String" />
      <MemberSignature Language="F#" Value="member this.GeoRegion : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.GeoRegion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.geoRegion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-133">Ruft die geographischen Standort für die App Service-Plan ab.</span><span class="sxs-lookup"><span data-stu-id="50fc7-133">Gets geographical location for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingEnvironmentProfile")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-134">Ruft ab, oder legt ihn fest-Spezifikation für die App Service-Umgebung für die App Service-Plan verwenden.</span><span class="sxs-lookup"><span data-stu-id="50fc7-134">Gets or sets specification for the App Service Environment to use for the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSpot">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSpot { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSpot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.IsSpot" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSpot As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSpot : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.IsSpot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isSpot")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-135">Ruft ab oder legt sie fest, wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; diese App Service-Plan Volltonfarbe Instanzen besitzt.</span><span class="sxs-lookup"><span data-stu-id="50fc7-135">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, this App Service Plan owns spot instances.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaximumNumberOfWorkers">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaximumNumberOfWorkers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaximumNumberOfWorkers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.MaximumNumberOfWorkers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaximumNumberOfWorkers As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaximumNumberOfWorkers : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.MaximumNumberOfWorkers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maximumNumberOfWorkers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-136">Ruft die maximale Anzahl von Instanzen, die dieser App Service-Plan zugewiesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="50fc7-136">Gets maximum number of instances that can be assigned to this App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfSites">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfSites { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfSites" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.NumberOfSites" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfSites As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfSites : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.NumberOfSites" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.numberOfSites")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-137">Ruft die Anzahl der apps diese App Service-Plan zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="50fc7-137">Gets number of apps assigned to this App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerSiteScaling">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PerSiteScaling { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PerSiteScaling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.PerSiteScaling" />
      <MemberSignature Language="VB.NET" Value="Public Property PerSiteScaling As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PerSiteScaling : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.PerSiteScaling" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.perSiteScaling")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-138">Ruft ab oder legt sie fest, wenn &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; apps diese App Service-Plan zugewiesen können unabhängig voneinander skaliert werden.</span><span class="sxs-lookup"><span data-stu-id="50fc7-138">Gets or sets if &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt;, apps assigned to this App Service plan can be scaled independently.</span></span>
            <span data-ttu-id="50fc7-139">Wenn &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt; apps diese App Service-Plan zugewiesen werden für alle Instanzen des Plans skaliert.</span><span class="sxs-lookup"><span data-stu-id="50fc7-139">If &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;, apps assigned to this App Service plan will scale to all instances of the plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.ProvisioningState" />
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
            <span data-ttu-id="50fc7-140">Ruft die Status der App Service-Umgebung bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="50fc7-140">Gets provisioning state of the App Service Environment.</span></span> <span data-ttu-id="50fc7-141">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen", "InProgress", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="50fc7-141">Possible values include: 'Succeeded', 'Failed', 'Canceled', 'InProgress', 'Deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reserved">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Reserved { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Reserved" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Reserved" />
      <MemberSignature Language="VB.NET" Value="Public Property Reserved As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Reserved : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Reserved" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="50fc7-142">Ruft ab, oder legt ihn fest reserviert.</span><span class="sxs-lookup"><span data-stu-id="50fc7-142">Gets or sets reserved.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.ResourceGroup" />
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
            <span data-ttu-id="50fc7-143">Ruft die Ressourcengruppe des App Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="50fc7-143">Gets resource group of the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuDescription Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As SkuDescription" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.WebSites.Models.SkuDescription with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpotExpirationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SpotExpirationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SpotExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.SpotExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property SpotExpirationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SpotExpirationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.SpotExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.spotExpirationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-144">Ruft ab oder legt die Uhrzeit des Ablaufs die Serverfarm.</span><span class="sxs-lookup"><span data-stu-id="50fc7-144">Gets or sets the time when the server farm expires.</span></span> <span data-ttu-id="50fc7-145">Nur gültig, wenn es sich um eine Volltonfarbe Serverfarm ist.</span><span class="sxs-lookup"><span data-stu-id="50fc7-145">Valid only if it is a spot server farm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of StatusOptions)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Status" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.StatusOptions&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-146">Ruft die Status der app Service-Plans.</span><span class="sxs-lookup"><span data-stu-id="50fc7-146">Gets app Service plan status.</span></span> <span data-ttu-id="50fc7-147">Folgende Werte sind möglich: "Bereit", "Ausstehend", "Erstellen"</span><span class="sxs-lookup"><span data-stu-id="50fc7-147">Possible values include: 'Ready', 'Pending', 'Creating'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subscription">
      <MemberSignature Language="C#" Value="public string Subscription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Subscription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Subscription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subscription As String" />
      <MemberSignature Language="F#" Value="member this.Subscription : string" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Subscription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subscription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-148">Ruft die app Service-Plan-Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="50fc7-148">Gets app Service plan subscription.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.TargetWorkerCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.TargetWorkerCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-149">Ruft ab oder legt Skalierung-Worker-Anzahl.</span><span class="sxs-lookup"><span data-stu-id="50fc7-149">Gets or sets scaling worker count.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetWorkerSizeId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TargetWorkerSizeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TargetWorkerSizeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.TargetWorkerSizeId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetWorkerSizeId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TargetWorkerSizeId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.TargetWorkerSizeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.targetWorkerSizeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-150">Ruft ab oder legt sie fest, Skalierung Worker Größe-ID.</span><span class="sxs-lookup"><span data-stu-id="50fc7-150">Gets or sets scaling worker size ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="appServicePlan.Validate " />
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
            <span data-ttu-id="50fc7-151">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="50fc7-151">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="50fc7-152">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="50fc7-152">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WorkerTierName">
      <MemberSignature Language="C#" Value="public string WorkerTierName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WorkerTierName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AppServicePlan.WorkerTierName" />
      <MemberSignature Language="VB.NET" Value="Public Property WorkerTierName As String" />
      <MemberSignature Language="F#" Value="member this.WorkerTierName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AppServicePlan.WorkerTierName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.workerTierName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="50fc7-153">Abrufen oder Festlegen der Ziel-workerebene für die App Service-Plan zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="50fc7-153">Gets or sets target worker tier assigned to the App Service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>