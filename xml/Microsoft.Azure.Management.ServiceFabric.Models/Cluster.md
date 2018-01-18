<Type Name="Cluster" FullName="Microsoft.Azure.Management.ServiceFabric.Models.Cluster">
  <TypeSignature Language="C#" Value="public class Cluster : Microsoft.Azure.Management.ServiceFabric.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Cluster extends Microsoft.Azure.Management.ServiceFabric.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceFabric.Models.Cluster" />
  <TypeSignature Language="VB.NET" Value="Public Class Cluster&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Cluster = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ServiceFabric.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="22f17-101">Die Clusterressource</span><span class="sxs-lookup"><span data-stu-id="22f17-101">The cluster resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22f17-102">Initialisiert eine neue Instanz der Cluster-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22f17-102">Initializes a new instance of the Cluster class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster (string location, string managementEndpoint, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; nodeTypes, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt; availableClusterVersions = null, string clusterId = null, string clusterState = null, string clusterEndpoint = null, string clusterCodeVersion = null, Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription certificate = null, string reliabilityLevel = null, string upgradeMode = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; clientCertificateThumbprints = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; clientCertificateCommonNames = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; fabricSettings = null, Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription reverseProxyCertificate = null, Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory azureActiveDirectory = null, string provisioningState = null, string vmImage = null, Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig diagnosticsStorageAccountConfig = null, Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy upgradeDescription = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string managementEndpoint, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; nodeTypes, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt; availableClusterVersions, string clusterId, string clusterState, string clusterEndpoint, string clusterCodeVersion, class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription certificate, string reliabilityLevel, string upgradeMode, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; clientCertificateThumbprints, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; clientCertificateCommonNames, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; fabricSettings, class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription reverseProxyCertificate, class Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory azureActiveDirectory, string provisioningState, string vmImage, class Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig diagnosticsStorageAccountConfig, class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails},System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint},System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName},System.Collections.Generic.IList{Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription},Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription,Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory,System.String,System.String,Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig,Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceFabric.Models.Cluster : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt; * string * string * string * string * Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; * Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription * Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory * string * string * Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig * Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy -&gt; Microsoft.Azure.Management.ServiceFabric.Models.Cluster" Usage="new Microsoft.Azure.Management.ServiceFabric.Models.Cluster (location, managementEndpoint, nodeTypes, id, name, type, tags, availableClusterVersions, clusterId, clusterState, clusterEndpoint, clusterCodeVersion, certificate, reliabilityLevel, upgradeMode, clientCertificateThumbprints, clientCertificateCommonNames, fabricSettings, reverseProxyCertificate, azureActiveDirectory, provisioningState, vmImage, diagnosticsStorageAccountConfig, upgradeDescription)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="managementEndpoint" Type="System.String" />
        <Parameter Name="nodeTypes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="availableClusterVersions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt;" />
        <Parameter Name="clusterId" Type="System.String" />
        <Parameter Name="clusterState" Type="System.String" />
        <Parameter Name="clusterEndpoint" Type="System.String" />
        <Parameter Name="clusterCodeVersion" Type="System.String" />
        <Parameter Name="certificate" Type="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" />
        <Parameter Name="reliabilityLevel" Type="System.String" />
        <Parameter Name="upgradeMode" Type="System.String" />
        <Parameter Name="clientCertificateThumbprints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt;" />
        <Parameter Name="clientCertificateCommonNames" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt;" />
        <Parameter Name="fabricSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt;" />
        <Parameter Name="reverseProxyCertificate" Type="Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription" />
        <Parameter Name="azureActiveDirectory" Type="Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="vmImage" Type="System.String" />
        <Parameter Name="diagnosticsStorageAccountConfig" Type="Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig" />
        <Parameter Name="upgradeDescription" Type="Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="22f17-103">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="22f17-103">Resource location.</span></span></param>
        <param name="managementEndpoint"><span data-ttu-id="22f17-104">Die http-verwaltungsendpunkt des Clusters</span><span class="sxs-lookup"><span data-stu-id="22f17-104">The http management endpoint of the cluster</span></span></param>
        <param name="nodeTypes"><span data-ttu-id="22f17-105">Die Liste der Nodetypes, die den Cluster bilden</span><span class="sxs-lookup"><span data-stu-id="22f17-105">The list of nodetypes that make up the cluster</span></span></param>
        <param name="id"><span data-ttu-id="22f17-106">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="22f17-106">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="22f17-107">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="22f17-107">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="22f17-108">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="22f17-108">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="22f17-109">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="22f17-109">Resource tags.</span></span></param>
        <param name="availableClusterVersions"><span data-ttu-id="22f17-110">Der verfügbaren Codeversion die auf der Cluster aktualisieren kann, die Sie UpgradeMode auf manuell so aktualisieren Sie auf auswählen müssen</span><span class="sxs-lookup"><span data-stu-id="22f17-110">The available cluster code version which the cluster can upgrade to, note that you must choose upgradeMode to manual to upgrade to</span></span></param>
        <param name="clusterId"><span data-ttu-id="22f17-111">Der eindeutige Bezeichner für die Clusterressource</span><span class="sxs-lookup"><span data-stu-id="22f17-111">The unique identifier for the cluster resource</span></span></param>
        <param name="clusterState"><span data-ttu-id="22f17-112">Der Status für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="22f17-112">The state for the cluster.</span></span> <span data-ttu-id="22f17-113">Folgende Werte sind möglich: "WaitingForNodes", "Bereitstellen", "BaselineUpgrade", "UpdatingUserConfiguration", "UpdatingUserCertificate", "UpdatingInfrastructure", "EnforcingClusterVersion", "UpgradeServiceUnreachable", "Automatisch skalieren", "Bereit"</span><span class="sxs-lookup"><span data-stu-id="22f17-113">Possible values include: 'WaitingForNodes', 'Deploying', 'BaselineUpgrade', 'UpdatingUserConfiguration', 'UpdatingUserCertificate', 'UpdatingInfrastructure', 'EnforcingClusterVersion', 'UpgradeServiceUnreachable', 'AutoScale', 'Ready'</span></span></param>
        <param name="clusterEndpoint"><span data-ttu-id="22f17-114">Der Endpunkt für den Cluster Herstellen einer Verbindung mit Servicefabric-Ressourcenanbieter</span><span class="sxs-lookup"><span data-stu-id="22f17-114">The endpoint for the cluster connecting to servicefabric resource provider</span></span></param>
        <param name="clusterCodeVersion"><span data-ttu-id="22f17-115">Die ServiceFabric Codeversion im Cluster ausgeführt wird</span><span class="sxs-lookup"><span data-stu-id="22f17-115">The ServiceFabric code version running in your cluster</span></span></param>
        <param name="certificate"><span data-ttu-id="22f17-116">Dieses Zertifikat für die primären wird als Knoten Clustersicherheit, SSL-Zertifikat für den Cluster Endpunkt und Standard Admin Verwaltungsclient verwendet werden</span><span class="sxs-lookup"><span data-stu-id="22f17-116">This primay certificate will be used as cluster node to node security, SSL certificate for cluster management endpoint and default admin client</span></span></param>
        <param name="reliabilityLevel"><span data-ttu-id="22f17-117">Zuverlässigkeit Clusterebene gibt die Größe des Systemdiensts Replikat an.</span><span class="sxs-lookup"><span data-stu-id="22f17-117">Cluster reliability level indicates replica set size of system service.</span></span> <span data-ttu-id="22f17-118">Folgende Werte sind möglich: "Bronze", "Silber", "Gold", "Platin"</span><span class="sxs-lookup"><span data-stu-id="22f17-118">Possible values include: 'Bronze', 'Silver', 'Gold', 'Platinum'</span></span></param>
        <param name="upgradeMode"><span data-ttu-id="22f17-119">Cluster-Upgrade-Modus gibt an, ob der Fabric-Upgrade vom System oder nicht automatisch initiiert wird.</span><span class="sxs-lookup"><span data-stu-id="22f17-119">Cluster upgrade mode indicates if fabric upgrade is initiated automatically by the system or not.</span></span> <span data-ttu-id="22f17-120">Folgende Werte sind möglich: 'Automatic', 'Manual'</span><span class="sxs-lookup"><span data-stu-id="22f17-120">Possible values include: 'Automatic', 'Manual'</span></span></param>
        <param name="clientCertificateThumbprints"><span data-ttu-id="22f17-121">Der Fingerabdruck Clientdetails, es dient für den Clientzugriff für Clustervorgang</span><span class="sxs-lookup"><span data-stu-id="22f17-121">The client thumbprint details ,it is used for client access for cluster operation</span></span></param>
        <param name="clientCertificateCommonNames"> <span data-ttu-id="22f17-122">Liste der Clientzertifikate Whitelist basierend auf den allgemeinen Namen</span><span class="sxs-lookup"><span data-stu-id="22f17-122">List of client certificates to whitelist based on common names</span></span></param>
        <param name="fabricSettings"><span data-ttu-id="22f17-123">Die Liste der benutzerdefinierten fabriceinstellungen, um den Cluster zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="22f17-123">List of custom fabric settings to configure the cluster.</span></span></param>
        <param name="reverseProxyCertificate"><span data-ttu-id="22f17-124">Das Serverzertifikat von reverse-Proxy verwendet</span><span class="sxs-lookup"><span data-stu-id="22f17-124">The server certificate used by reverse proxy</span></span></param>
        <param name="azureActiveDirectory"><span data-ttu-id="22f17-125">Die Einstellungen zum Aktivieren der AAD-Authentifizierung auf dem cluster</span><span class="sxs-lookup"><span data-stu-id="22f17-125">The settings to enable AAD authentication on the cluster</span></span></param>
        <param name="provisioningState"><span data-ttu-id="22f17-126">Der Bereitstellungsstatus der Clusterressource.</span><span class="sxs-lookup"><span data-stu-id="22f17-126">The provisioning state of the cluster resource.</span></span> <span data-ttu-id="22f17-127">Folgende Werte sind möglich: "Aktualisieren", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="22f17-127">Possible values include: 'Updating', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="vmImage"><span data-ttu-id="22f17-128">Der Name des VM-Image VMSS wurde mit konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="22f17-128">The name of VM image VMSS has been configured with.</span></span> <span data-ttu-id="22f17-129">Allgemeine Namen wie z. B. Windows oder Linux können verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="22f17-129">Generic names such as Windows or Linux can be used.</span></span></param>
        <param name="diagnosticsStorageAccountConfig"><span data-ttu-id="22f17-130">Die Speicherdiagnose Konto Konfigurationsdetails</span><span class="sxs-lookup"><span data-stu-id="22f17-130">The storage diagnostics account configuration details</span></span></param>
        <param name="upgradeDescription"><span data-ttu-id="22f17-131">Die Richtlinie beim Aktualisieren des Clusters verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="22f17-131">The policy to use when upgrading the cluster.</span></span></param>
        <summary>
            <span data-ttu-id="22f17-132">Initialisiert eine neue Instanz der Cluster-Klasse.</span><span class="sxs-lookup"><span data-stu-id="22f17-132">Initializes a new instance of the Cluster class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableClusterVersions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt; AvailableClusterVersions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt; AvailableClusterVersions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.AvailableClusterVersions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailableClusterVersions As IList(Of ClusterVersionDetails)" />
      <MemberSignature Language="F#" Value="member this.AvailableClusterVersions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt;" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.AvailableClusterVersions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.availableClusterVersions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClusterVersionDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-133">Ruft die verfügbare Cluster code Version, die den Cluster, aktualisieren kann Beachten Sie, dass Sie UpgradeMode auf manuell so aktualisieren Sie auf auswählen müssen</span><span class="sxs-lookup"><span data-stu-id="22f17-133">Gets the available cluster code version which the cluster can upgrade to, note that you must choose upgradeMode to manual to upgrade to</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureActiveDirectory">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory AzureActiveDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory AzureActiveDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.AzureActiveDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureActiveDirectory As AzureActiveDirectory" />
      <MemberSignature Language="F#" Value="member this.AzureActiveDirectory : Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.AzureActiveDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureActiveDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.AzureActiveDirectory</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-134">Ruft ab oder legt die Einstellungen zum Aktivieren der AAD-Authentifizierung auf dem cluster</span><span class="sxs-lookup"><span data-stu-id="22f17-134">Gets or sets the settings to enable AAD authentication on the cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription Certificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription Certificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.Certificate" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificate As CertificateDescription" />
      <MemberSignature Language="F#" Value="member this.Certificate : Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.Certificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-135">Ruft ab oder legt fest, denen dieses Zertifikat für die primären als verwendet wird, cluster Knoten Sicherheit, SSL-Zertifikat für den Cluster Management Endpunkt und Standard-Admin-client</span><span class="sxs-lookup"><span data-stu-id="22f17-135">Gets or sets this primay certificate will be used as cluster node to node security, SSL certificate for cluster management endpoint and default admin client</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertificateCommonNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; ClientCertificateCommonNames { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; ClientCertificateCommonNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClientCertificateCommonNames" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertificateCommonNames As IList(Of ClientCertificateCommonName)" />
      <MemberSignature Language="F#" Value="member this.ClientCertificateCommonNames : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClientCertificateCommonNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertificateCommonNames")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateCommonName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-136">Ruft ab, oder legt Sie Liste der Clientzertifikate Whitelist basierend auf den allgemeinen Namen fest.</span><span class="sxs-lookup"><span data-stu-id="22f17-136">Gets or sets  List of client certificates to whitelist based on common names</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertificateThumbprints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; ClientCertificateThumbprints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; ClientCertificateThumbprints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClientCertificateThumbprints" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientCertificateThumbprints As IList(Of ClientCertificateThumbprint)" />
      <MemberSignature Language="F#" Value="member this.ClientCertificateThumbprints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClientCertificateThumbprints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clientCertificateThumbprints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.ClientCertificateThumbprint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-137">Ruft ab oder legt Sie den Client Fingerabdruck Details, es dient für den Clientzugriff für Clustervorgang</span><span class="sxs-lookup"><span data-stu-id="22f17-137">Gets or sets the client thumbprint details ,it is used for client access for cluster operation</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterCodeVersion">
      <MemberSignature Language="C#" Value="public string ClusterCodeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterCodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterCodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property ClusterCodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.ClusterCodeVersion : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterCodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterCodeVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-138">Ruft ab oder legt die ServiceFabric Codeversion im Cluster ausgeführt wird</span><span class="sxs-lookup"><span data-stu-id="22f17-138">Gets or sets the ServiceFabric code version running in your cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterEndpoint">
      <MemberSignature Language="C#" Value="public string ClusterEndpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ClusterEndpoint : string" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-139">Ruft den Endpunkt für den Cluster Herstellen einer Verbindung mit Servicefabric Ressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="22f17-139">Gets the endpoint for the cluster connecting to servicefabric resource provider</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterId">
      <MemberSignature Language="C#" Value="public string ClusterId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterId As String" />
      <MemberSignature Language="F#" Value="member this.ClusterId : string" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-140">Ruft den eindeutigen Bezeichner für die Clusterressource</span><span class="sxs-lookup"><span data-stu-id="22f17-140">Gets the unique identifier for the cluster resource</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterState">
      <MemberSignature Language="C#" Value="public string ClusterState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterState As String" />
      <MemberSignature Language="F#" Value="member this.ClusterState : string" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ClusterState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.clusterState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-141">Ruft den Zustand für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="22f17-141">Gets the state for the cluster.</span></span> <span data-ttu-id="22f17-142">Folgende Werte sind möglich: "WaitingForNodes", "Bereitstellen", "BaselineUpgrade", "UpdatingUserConfiguration", "UpdatingUserCertificate", "UpdatingInfrastructure", "EnforcingClusterVersion", "UpgradeServiceUnreachable", "Automatisch skalieren", "Bereit"</span><span class="sxs-lookup"><span data-stu-id="22f17-142">Possible values include: 'WaitingForNodes', 'Deploying', 'BaselineUpgrade', 'UpdatingUserConfiguration', 'UpdatingUserCertificate', 'UpdatingInfrastructure', 'EnforcingClusterVersion', 'UpgradeServiceUnreachable', 'AutoScale', 'Ready'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsStorageAccountConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig DiagnosticsStorageAccountConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig DiagnosticsStorageAccountConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.DiagnosticsStorageAccountConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DiagnosticsStorageAccountConfig As DiagnosticsStorageAccountConfig" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsStorageAccountConfig : Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.DiagnosticsStorageAccountConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.diagnosticsStorageAccountConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.DiagnosticsStorageAccountConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-143">Ruft ab oder legt die Speicherdiagnose Kontodetails-Konfiguration</span><span class="sxs-lookup"><span data-stu-id="22f17-143">Gets or sets the storage diagnostics account configuration details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; FabricSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; FabricSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.FabricSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property FabricSettings As IList(Of SettingsSectionDescription)" />
      <MemberSignature Language="F#" Value="member this.FabricSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.FabricSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.fabricSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.SettingsSectionDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-144">Ruft ab oder legt die Liste der benutzerdefinierten fabriceinstellungen, um den Cluster zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="22f17-144">Gets or sets list of custom fabric settings to configure the cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagementEndpoint">
      <MemberSignature Language="C#" Value="public string ManagementEndpoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ManagementEndpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ManagementEndpoint" />
      <MemberSignature Language="VB.NET" Value="Public Property ManagementEndpoint As String" />
      <MemberSignature Language="F#" Value="member this.ManagementEndpoint : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ManagementEndpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.managementEndpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-145">Ruft ab oder legt den http-verwaltungsendpunkt des Clusters</span><span class="sxs-lookup"><span data-stu-id="22f17-145">Gets or sets the http management endpoint of the cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeTypes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; NodeTypes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; NodeTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.NodeTypes" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeTypes As IList(Of NodeTypeDescription)" />
      <MemberSignature Language="F#" Value="member this.NodeTypes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.NodeTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeTypes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.ServiceFabric.Models.NodeTypeDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-146">Ruft ab oder legt die Liste der Nodetypes, die den Cluster bilden</span><span class="sxs-lookup"><span data-stu-id="22f17-146">Gets or sets the list of nodetypes that make up the cluster</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="22f17-147">Ruft den Bereitstellungsstatus der Clusterressource ab.</span><span class="sxs-lookup"><span data-stu-id="22f17-147">Gets the provisioning state of the cluster resource.</span></span> <span data-ttu-id="22f17-148">Folgende Werte sind möglich: "Aktualisieren", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "Abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="22f17-148">Possible values include: 'Updating', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReliabilityLevel">
      <MemberSignature Language="C#" Value="public string ReliabilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReliabilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ReliabilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property ReliabilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.ReliabilityLevel : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ReliabilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reliabilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-149">Ruft ab oder legt ihn fest Cluster Zuverlässigkeit der Replikatgruppe des Systemdiensts angibt.</span><span class="sxs-lookup"><span data-stu-id="22f17-149">Gets or sets cluster reliability level indicates replica set size of system service.</span></span> <span data-ttu-id="22f17-150">Folgende Werte sind möglich: "Bronze", "Silber", "Gold", "Platin"</span><span class="sxs-lookup"><span data-stu-id="22f17-150">Possible values include: 'Bronze', 'Silver', 'Gold', 'Platinum'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReverseProxyCertificate">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription ReverseProxyCertificate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription ReverseProxyCertificate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ReverseProxyCertificate" />
      <MemberSignature Language="VB.NET" Value="Public Property ReverseProxyCertificate As CertificateDescription" />
      <MemberSignature Language="F#" Value="member this.ReverseProxyCertificate : Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.ReverseProxyCertificate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.reverseProxyCertificate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.CertificateDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-151">Ruft ab oder legt das Serverzertifikat von reverse-Proxy verwendet</span><span class="sxs-lookup"><span data-stu-id="22f17-151">Gets or sets the server certificate used by reverse proxy</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy UpgradeDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDescription As ClusterUpgradePolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeDescription")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceFabric.Models.ClusterUpgradePolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-152">Ruft ab oder legt die Richtlinie beim Aktualisieren des Clusters verwendet.</span><span class="sxs-lookup"><span data-stu-id="22f17-152">Gets or sets the policy to use when upgrading the cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public string UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.UpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.upgradeMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-153">Ruft ab oder legt ihn fest-clusterupgrade Modus gibt an, wenn Fabric-Upgrade vom System oder nicht automatisch initiiert wird.</span><span class="sxs-lookup"><span data-stu-id="22f17-153">Gets or sets cluster upgrade mode indicates if fabric upgrade is initiated automatically by the system or not.</span></span> <span data-ttu-id="22f17-154">Folgende Werte sind möglich: 'Automatic', 'Manual'</span><span class="sxs-lookup"><span data-stu-id="22f17-154">Possible values include: 'Automatic', 'Manual'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="cluster.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="22f17-155">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="22f17-155">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="22f17-156">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="22f17-156">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmImage">
      <MemberSignature Language="C#" Value="public string VmImage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceFabric.Models.Cluster.VmImage" />
      <MemberSignature Language="VB.NET" Value="Public Property VmImage As String" />
      <MemberSignature Language="F#" Value="member this.VmImage : string with get, set" Usage="Microsoft.Azure.Management.ServiceFabric.Models.Cluster.VmImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceFabric</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmImage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="22f17-157">Ruft ab oder legt den Namen der VM-Image, das VMSS konfiguriert worden ist.</span><span class="sxs-lookup"><span data-stu-id="22f17-157">Gets or sets the name of VM image VMSS has been configured with.</span></span>
            <span data-ttu-id="22f17-158">Allgemeine Namen wie z. B. Windows oder Linux können verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="22f17-158">Generic names such as Windows or Linux can be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>