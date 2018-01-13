<Type Name="SearchService" FullName="Microsoft.Azure.Management.Search.Models.SearchService">
  <TypeSignature Language="C#" Value="public class SearchService : Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SearchService extends Microsoft.Azure.Management.Search.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.Models.SearchService" />
  <TypeSignature Language="VB.NET" Value="Public Class SearchService&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type SearchService = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Search.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c6e8d-101">Beschreibt einen Azure Search-Dienst und seinem aktuellen Status.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-101">Describes an Azure Search service and its current state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-102">Initialisiert eine neue Instanz der SearchService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-102">Initializes a new instance of the SearchService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SearchService (string location, Microsoft.Azure.Management.Search.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;int&gt; replicaCount = null, Nullable&lt;int&gt; partitionCount = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status = null, string statusDetails = null, Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Search.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;int32&gt; replicaCount, valuetype System.Nullable`1&lt;int32&gt; partitionCount, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; hostingMode, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; status, string statusDetails, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.#ctor(System.String,Microsoft.Azure.Management.Search.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Management.Search.Models.HostingMode},System.Nullable{Microsoft.Azure.Management.Search.Models.SearchServiceStatus},System.String,System.Nullable{Microsoft.Azure.Management.Search.Models.ProvisioningState})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Search.Models.SearchService : string * Microsoft.Azure.Management.Search.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; * Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; * string * Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="new Microsoft.Azure.Management.Search.Models.SearchService (location, sku, id, name, type, tags, replicaCount, partitionCount, hostingMode, status, statusDetails, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Search.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="replicaCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="partitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="hostingMode" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" />
        <Parameter Name="statusDetails" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="c6e8d-103">Der geografische Standort der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-103">The geographic location of the resource.</span></span>
            <span data-ttu-id="c6e8d-104">Diese Angabe muss eines der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</span><span class="sxs-lookup"><span data-stu-id="c6e8d-104">This must be one of the supported and registered Azure Geo Regions (for example, West US, East US, Southeast Asia, and so forth).</span></span></param>
        <param name="sku"><span data-ttu-id="c6e8d-105">Die SKU des Search-Dienst, der bestimmt, Preis, Ebenen und Kapazitätsgrenzen.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-105">The SKU of the Search Service, which determines price tier and capacity limits.</span></span></param>
        <param name="id"><span data-ttu-id="c6e8d-106">Die ID der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-106">The ID of the resource.</span></span> <span data-ttu-id="c6e8d-107">Dies kann mit der Azure-Ressourcen-Manager verwendet werden Ressourcen miteinander verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-107">This can be used with the Azure Resource Manager to link resources together.</span></span></param>
        <param name="name"><span data-ttu-id="c6e8d-108">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-108">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="c6e8d-109">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-109">The resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="c6e8d-110">Tags helfen, die Ressource im Azure-Portal zu kategorisieren.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-110">Tags to help categorize the resource in the Azure portal.</span></span></param>
        <param name="replicaCount"><span data-ttu-id="c6e8d-111">Die Anzahl der Replikate in der Search-Dienst.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-111">The number of replicas in the Search service.</span></span> <span data-ttu-id="c6e8d-112">Wenn angegeben, muss es einen Wert zwischen 1 und 12 einschließlich für standard-SKUs oder zwischen 1 und 3 für SKUs vom Typ basic inklusive.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-112">If specified, it must be a value between 1 and 12 inclusive for standard SKUs or between 1 and 3 inclusive for basic SKU.</span></span></param>
        <param name="partitionCount"><span data-ttu-id="c6e8d-113">Die Anzahl der Partitionen in der Search-Dienst; Wenn angegeben, kann es 1, 2, 3, 4, 6 oder 12.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-113">The number of partitions in the Search service; if specified, it can be 1, 2, 3, 4, 6, or 12.</span></span>
            <span data-ttu-id="c6e8d-114">Werte größer als 1 sind nur für standard-SKUs gültig.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-114">Values greater than 1 are only valid for standard SKUs.</span></span> <span data-ttu-id="c6e8d-115">Für "standard3"-Dienste mit HostingMode "HighDensity" festgelegt werden die zulässigen Werte zwischen 1 und 3 ein.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-115">For 'standard3' services with hostingMode set to 'highDensity', the allowed values are between 1 and 3.</span></span></param>
        <param name="hostingMode"><span data-ttu-id="c6e8d-116">Gilt nur für die SKU standard3.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-116">Applicable only for the standard3 SKU.</span></span>
            <span data-ttu-id="c6e8d-117">Sie können festlegen, dass diese Eigenschaft zum Aktivieren von bis zu 3 – hohe Dichte Partitionen, die bis zu 1.000-Indizes ermöglichen, dies ist sehr viel höher als die maximale Indizes für beliebige andere SKU zulässig.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-117">You can set this property to enable up to 3 high density partitions that allow up to 1000 indexes, which is much higher than the maximum indexes allowed for any other SKU.</span></span> <span data-ttu-id="c6e8d-118">Für die SKU standard3 ist der Wert "Default" oder "HighDensity".</span><span class="sxs-lookup"><span data-stu-id="c6e8d-118">For the standard3 SKU, the value is either 'default' or 'highDensity'.</span></span>
            <span data-ttu-id="c6e8d-119">Für alle anderen SKUs muss dieser Wert "Default" sein.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-119">For all other SKUs, this value must be 'default'.</span></span> <span data-ttu-id="c6e8d-120">Folgende Werte sind möglich: "Default", "HighDensity"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-120">Possible values include: 'default', 'highDensity'</span></span></param>
        <param name="status"><span data-ttu-id="c6e8d-121">Der Status des Suchdiensts.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-121">The status of the Search service.</span></span> <span data-ttu-id="c6e8d-122">Folgende Werte sind möglich: "wird ausgeführt": die Search-Dienst ausgeführt wird und keine Bereitstellung Vorgänge ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-122">Possible values include: 'running': The Search service is running and no provisioning operations are underway.</span></span> <span data-ttu-id="c6e8d-123">'Bereitstellung': der Suchdienst wird bereitgestellt, oder nach oben oder unten skaliert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-123">'provisioning': The Search service is being provisioned or scaled up or down.</span></span> <span data-ttu-id="c6e8d-124">"deleting": der Suchdienst wird gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-124">'deleting': The Search service is being deleted.</span></span> <span data-ttu-id="c6e8d-125">"heruntergestuft": der Suchdienst wird heruntergestuft.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-125">'degraded': The Search service is degraded.</span></span> <span data-ttu-id="c6e8d-126">Dies kann auftreten, wenn die zugrunde liegenden sucheinheiten nicht fehlerfrei sind.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-126">This can occur when the underlying search units are not healthy.</span></span> <span data-ttu-id="c6e8d-127">Der Suchdienst ist wahrscheinlich betriebsbereit, aber möglicherweise ist er langsam und einige Anforderungen werden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-127">The Search service is most likely operational, but performance might be slow and some requests might be dropped.</span></span> <span data-ttu-id="c6e8d-128">"disabled": der Suchdienst wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-128">'disabled': The Search service is disabled.</span></span> <span data-ttu-id="c6e8d-129">Mit diesem Status lehnt der Dienst alle API-Anforderungen ab.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-129">In this state, the service will reject all API requests.</span></span> <span data-ttu-id="c6e8d-130">"Fehler": der Suchdienst wird im Status "Fehler".</span><span class="sxs-lookup"><span data-stu-id="c6e8d-130">'error': The Search service is in an error state.</span></span> <span data-ttu-id="c6e8d-131">Wenn Ihr Dienst in der eingeschränkter deaktiviert oder Fehler angibt ist, bedeutet dies, dass das Azure Search-Team, das zugrunde liegende Problem untersuchen ist.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-131">If your service is in the degraded, disabled, or error states, it means the Azure Search team is actively investigating the underlying issue.</span></span>
            <span data-ttu-id="c6e8d-132">Dedizierte Dienste mit diesen Status sind weiterhin auf Basis der Anzahl der bereitgestellten Sucheinheiten fakturierbar.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-132">Dedicated services in these states are still chargeable based on the number of search units provisioned.</span></span> <span data-ttu-id="c6e8d-133">Folgende Werte sind möglich: "wird ausgeführt", "Bereitstellung", "löschen", "heruntergestuft", "disabled", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-133">Possible values include: 'running', 'provisioning', 'deleting', 'degraded', 'disabled', 'error'</span></span></param>
        <param name="statusDetails"><span data-ttu-id="c6e8d-134">Die Details des Status des Search-Diensts.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-134">The details of the Search service status.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="c6e8d-135">Der Status des letzten Vorgangs für die Bereitstellung, die auf der Search-Dienst ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-135">The state of the last provisioning operation performed on the Search service.</span></span> <span data-ttu-id="c6e8d-136">Die Bereitstellung ist ein vorübergehender Zustand während der Einrichtung der Dienstkapazität.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-136">Provisioning is an intermediate state that occurs while service capacity is being established.</span></span> <span data-ttu-id="c6e8d-137">Nach Kapazität eingerichtet ist, wird ProvisioningState auf "erfolgreich abgeschlossen" oder "fehlgeschlagen" geändert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-137">After capacity is set up, provisioningState changes to either 'succeeded' or 'failed'.</span></span> <span data-ttu-id="c6e8d-138">Clientanwendungen können Bereitstellungsstatus (empfohlene Abrufintervall liegt zwischen 30 Sekunden und einer Minute) abrufen, mit der Search-Dienst abrufen Vorgang angezeigt, wenn ein Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-138">Client applications can poll provisioning status (the recommended polling interval is from 30 seconds to one minute) by using the Get Search Service operation to see when an operation is completed.</span></span> <span data-ttu-id="c6e8d-139">Wenn Sie den kostenlosen Dienst verwenden, neigt dieser Wert als "erfolgreich direkt im Aufruf der Suchdienst erstellen" zurückkehren.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-139">If you are using the free service, this value tends to come back as 'succeeded' directly in the call to Create Search service.</span></span> <span data-ttu-id="c6e8d-140">Grund hierfür ist, dass der kostenlose Dienst bereits eingerichtete Kapazitäten verwendet.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-140">This is because the free service uses capacity that is already set up.</span></span> <span data-ttu-id="c6e8d-141">Folgende Werte sind möglich: "erfolgreich abgeschlossen", "Bereitstellung", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-141">Possible values include: 'succeeded', 'provisioning', 'failed'</span></span></param>
        <summary>
            <span data-ttu-id="c6e8d-142">Initialisiert eine neue Instanz der SearchService-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-142">Initializes a new instance of the SearchService class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.HostingMode&gt; HostingMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberSignature Language="VB.NET" Value="Public Property HostingMode As Nullable(Of HostingMode)" />
      <MemberSignature Language="F#" Value="member this.HostingMode : Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.HostingMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostingMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.HostingMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-143">Ruft ab oder legt gilt nur für die SKU standard3.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-143">Gets or sets applicable only for the standard3 SKU.</span></span> <span data-ttu-id="c6e8d-144">Sie können festlegen, dass diese Eigenschaft zum Aktivieren von bis zu 3 – hohe Dichte Partitionen, die bis zu 1.000-Indizes ermöglichen, dies ist sehr viel höher als die maximale Indizes für beliebige andere SKU zulässig.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-144">You can set this property to enable up to 3 high density partitions that allow up to 1000 indexes, which is much higher than the maximum indexes allowed for any other SKU.</span></span> <span data-ttu-id="c6e8d-145">Für die SKU standard3 ist der Wert "Default" oder "HighDensity".</span><span class="sxs-lookup"><span data-stu-id="c6e8d-145">For the standard3 SKU, the value is either 'default' or 'highDensity'.</span></span> <span data-ttu-id="c6e8d-146">Für alle anderen SKUs muss dieser Wert "Default" sein.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-146">For all other SKUs, this value must be 'default'.</span></span> <span data-ttu-id="c6e8d-147">Folgende Werte sind möglich: "Default", "HighDensity"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-147">Possible values include: 'default', 'highDensity'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.PartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.partitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-148">Ruft ab oder legt die Anzahl der Partitionen in der Search-Dienst fest. Wenn angegeben, kann es 1, 2, 3, 4, 6 oder 12.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-148">Gets or sets the number of partitions in the Search service; if specified, it can be 1, 2, 3, 4, 6, or 12.</span></span> <span data-ttu-id="c6e8d-149">Werte größer als 1 sind nur für standard-SKUs gültig.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-149">Values greater than 1 are only valid for standard SKUs.</span></span> <span data-ttu-id="c6e8d-150">Für "standard3"-Dienste mit HostingMode "HighDensity" festgelegt werden die zulässigen Werte zwischen 1 und 3 ein.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-150">For 'standard3' services with hostingMode set to 'highDensity', the allowed values are between 1 and 3.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.ProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of ProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.ProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-151">Ruft der Status der letzten Operation für die Search-Dienst bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-151">Gets the state of the last provisioning operation performed on the Search service.</span></span> <span data-ttu-id="c6e8d-152">Die Bereitstellung ist ein vorübergehender Zustand während der Einrichtung der Dienstkapazität.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-152">Provisioning is an intermediate state that occurs while service capacity is being established.</span></span> <span data-ttu-id="c6e8d-153">Nach Kapazität eingerichtet ist, wird ProvisioningState auf "erfolgreich abgeschlossen" oder "fehlgeschlagen" geändert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-153">After capacity is set up, provisioningState changes to either 'succeeded' or 'failed'.</span></span> <span data-ttu-id="c6e8d-154">Clientanwendungen können Bereitstellungsstatus (empfohlene Abrufintervall liegt zwischen 30 Sekunden und einer Minute) abrufen, mit der Search-Dienst abrufen Vorgang angezeigt, wenn ein Vorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-154">Client applications can poll provisioning status (the recommended polling interval is from 30 seconds to one minute) by using the Get Search Service operation to see when an operation is completed.</span></span> <span data-ttu-id="c6e8d-155">Wenn Sie den kostenlosen Dienst verwenden, neigt dieser Wert als "erfolgreich direkt im Aufruf der Suchdienst erstellen" zurückkehren.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-155">If you are using the free service, this value tends to come back as 'succeeded' directly in the call to Create Search service.</span></span> <span data-ttu-id="c6e8d-156">Grund hierfür ist, dass der kostenlose Dienst bereits eingerichtete Kapazitäten verwendet.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-156">This is because the free service uses capacity that is already set up.</span></span> <span data-ttu-id="c6e8d-157">Folgende Werte sind möglich: "erfolgreich abgeschlossen", "Bereitstellung", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-157">Possible values include: 'succeeded', 'provisioning', 'failed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ReplicaCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ReplicaCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ReplicaCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.ReplicaCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.replicaCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-158">Ruft ab oder legt die Anzahl der Replikate in der Search-Dienst fest.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-158">Gets or sets the number of replicas in the Search service.</span></span> <span data-ttu-id="c6e8d-159">Wenn angegeben, muss es einen Wert zwischen 1 und 12 einschließlich für standard-SKUs oder zwischen 1 und 3 für SKUs vom Typ basic inklusive.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-159">If specified, it must be a value between 1 and 12 inclusive for standard SKUs or between 1 and 3 inclusive for basic SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Search.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Search.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Search.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-160">Ruft ab oder legt die SKU des Search-Dienst, der bestimmt, price-Ebene und Kapazitätsgrenzen.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-160">Gets or sets the SKU of the Search Service, which determines price tier and capacity limits.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of SearchServiceStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;" Usage="Microsoft.Azure.Management.Search.Models.SearchService.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Search.Models.SearchServiceStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-161">Ruft den Status des Suchdiensts ab.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-161">Gets the status of the Search service.</span></span> <span data-ttu-id="c6e8d-162">Folgende Werte sind möglich: "wird ausgeführt": die Search-Dienst ausgeführt wird und keine Bereitstellung Vorgänge ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-162">Possible values include: 'running': The Search service is running and no provisioning operations are underway.</span></span> <span data-ttu-id="c6e8d-163">'Bereitstellung': der Suchdienst wird bereitgestellt, oder nach oben oder unten skaliert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-163">'provisioning': The Search service is being provisioned or scaled up or down.</span></span> <span data-ttu-id="c6e8d-164">"deleting": der Suchdienst wird gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-164">'deleting': The Search service is being deleted.</span></span> <span data-ttu-id="c6e8d-165">"heruntergestuft": der Suchdienst wird heruntergestuft.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-165">'degraded': The Search service is degraded.</span></span> <span data-ttu-id="c6e8d-166">Dies kann auftreten, wenn die zugrunde liegenden sucheinheiten nicht fehlerfrei sind.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-166">This can occur when the underlying search units are not healthy.</span></span> <span data-ttu-id="c6e8d-167">Der Suchdienst ist wahrscheinlich betriebsbereit, aber möglicherweise ist er langsam und einige Anforderungen werden gelöscht.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-167">The Search service is most likely operational, but performance might be slow and some requests might be dropped.</span></span>
            <span data-ttu-id="c6e8d-168">"disabled": der Suchdienst wird deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-168">'disabled': The Search service is disabled.</span></span> <span data-ttu-id="c6e8d-169">Mit diesem Status lehnt der Dienst alle API-Anforderungen ab.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-169">In this state, the service will reject all API requests.</span></span> <span data-ttu-id="c6e8d-170">"Fehler": der Suchdienst wird im Status "Fehler".</span><span class="sxs-lookup"><span data-stu-id="c6e8d-170">'error': The Search service is in an error state.</span></span> <span data-ttu-id="c6e8d-171">Wenn Ihr Dienst in der eingeschränkter deaktiviert oder Fehler angibt ist, bedeutet dies, dass das Azure Search-Team, das zugrunde liegende Problem untersuchen ist.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-171">If your service is in the degraded, disabled, or error states, it means the Azure Search team is actively investigating the underlying issue.</span></span> <span data-ttu-id="c6e8d-172">Dedizierte Dienste mit diesen Status sind weiterhin auf Basis der Anzahl der bereitgestellten Sucheinheiten fakturierbar.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-172">Dedicated services in these states are still chargeable based on the number of search units provisioned.</span></span> <span data-ttu-id="c6e8d-173">Folgende Werte sind möglich: "wird ausgeführt", "Bereitstellung", "löschen", "heruntergestuft", "disabled", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="c6e8d-173">Possible values include: 'running', 'provisioning', 'deleting', 'degraded', 'disabled', 'error'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StatusDetails">
      <MemberSignature Language="C#" Value="public string StatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StatusDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.StatusDetails : string" Usage="Microsoft.Azure.Management.Search.Models.SearchService.StatusDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.statusDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-174">Ruft die Details des suchen-Dienststatus ab.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-174">Gets the details of the Search service status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.Models.SearchService.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="searchService.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c6e8d-175">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c6e8d-175">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c6e8d-176">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c6e8d-176">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>