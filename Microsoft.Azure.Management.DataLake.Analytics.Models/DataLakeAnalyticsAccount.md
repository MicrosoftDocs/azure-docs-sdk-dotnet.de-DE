<Type Name="DataLakeAnalyticsAccount" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccount : Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccount extends Microsoft.Azure.Management.DataLake.Analytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccount&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccount = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="6ae4c-101">Ein Data Lake Analytics-Kontoobjekt, enthält alle Informationen, die dem benannten Data Lake Analytics-Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-101">A Data Lake Analytics account object, containing all information associated with the named Data Lake Analytics account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-102">Initialisiert eine neue Instanz der DataLakeAnalyticsAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-102">Initializes a new instance of the DataLakeAnalyticsAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccount (string location, string defaultDataLakeStoreAccount, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;DateTime&gt; lastModifiedTime = null, string endpoint = null, Nullable&lt;Guid&gt; accountId = null, Nullable&lt;int&gt; maxDegreeOfParallelism = null, Nullable&lt;int&gt; queryStoreRetention = null, Nullable&lt;int&gt; maxJobCount = null, Nullable&lt;int&gt; systemMaxDegreeOfParallelism = null, Nullable&lt;int&gt; systemMaxJobCount = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules = null, Nullable&lt;int&gt; maxDegreeOfParallelismPerJob = null, Nullable&lt;int&gt; minPriorityPerJob = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string defaultDataLakeStoreAccount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; dataLakeStoreAccounts, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModifiedTime, string endpoint, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; accountId, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; queryStoreRetention, valuetype System.Nullable`1&lt;int32&gt; maxJobCount, valuetype System.Nullable`1&lt;int32&gt; systemMaxDegreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; systemMaxJobCount, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; storageAccounts, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; newTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; currentTier, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; firewallState, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; firewallAllowAzureIps, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; firewallRules, valuetype System.Nullable`1&lt;int32&gt; maxDegreeOfParallelismPerJob, valuetype System.Nullable`1&lt;int32&gt; minPriorityPerJob, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; computePolicies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.#ctor(System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo},System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Guid},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.TierType},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (location As String, defaultDataLakeStoreAccount As String, dataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional provisioningState As Nullable(Of DataLakeAnalyticsAccountStatus) = null, Optional state As Nullable(Of DataLakeAnalyticsAccountState) = null, Optional creationTime As Nullable(Of DateTime) = null, Optional lastModifiedTime As Nullable(Of DateTime) = null, Optional endpoint As String = null, Optional accountId As Nullable(Of Guid) = null, Optional maxDegreeOfParallelism As Nullable(Of Integer) = null, Optional queryStoreRetention As Nullable(Of Integer) = null, Optional maxJobCount As Nullable(Of Integer) = null, Optional systemMaxDegreeOfParallelism As Nullable(Of Integer) = null, Optional systemMaxJobCount As Nullable(Of Integer) = null, Optional storageAccounts As IList(Of StorageAccountInfo) = null, Optional newTier As Nullable(Of TierType) = null, Optional currentTier As Nullable(Of TierType) = null, Optional firewallState As Nullable(Of FirewallState) = null, Optional firewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState) = null, Optional firewallRules As IList(Of FirewallRule) = null, Optional maxDegreeOfParallelismPerJob As Nullable(Of Integer) = null, Optional minPriorityPerJob As Nullable(Of Integer) = null, Optional computePolicies As IList(Of ComputePolicyAccountCreateParameters) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount : string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;Guid&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount (location, defaultDataLakeStoreAccount, dataLakeStoreAccounts, id, name, type, tags, provisioningState, state, creationTime, lastModifiedTime, endpoint, accountId, maxDegreeOfParallelism, queryStoreRetention, maxJobCount, systemMaxDegreeOfParallelism, systemMaxJobCount, storageAccounts, newTier, currentTier, firewallState, firewallAllowAzureIps, firewallRules, maxDegreeOfParallelismPerJob, minPriorityPerJob, computePolicies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="defaultDataLakeStoreAccount" Type="System.String" />
        <Parameter Name="dataLakeStoreAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastModifiedTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endpoint" Type="System.String" />
        <Parameter Name="accountId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="maxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="queryStoreRetention" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxDegreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="systemMaxJobCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;" />
        <Parameter Name="newTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="currentTier" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" />
        <Parameter Name="firewallState" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;" />
        <Parameter Name="firewallAllowAzureIps" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;" />
        <Parameter Name="firewallRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;" />
        <Parameter Name="maxDegreeOfParallelismPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="minPriorityPerJob" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="computePolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="6ae4c-103">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="6ae4c-103">Resource location</span></span></param>
        <param name="defaultDataLakeStoreAccount"><span data-ttu-id="6ae4c-104">Der Standardwert Data Lake-Speicher-Konto dieses Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-104">the default data lake storage account associated with this Data Lake Analytics account.</span></span></param>
        <param name="dataLakeStoreAccounts"><span data-ttu-id="6ae4c-105">die Liste der Data Lake-Speicherkonten, die diesem Konto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-105">the list of Data Lake storage accounts associated with this account.</span></span></param>
        <param name="id"><span data-ttu-id="6ae4c-106">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="6ae4c-106">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="6ae4c-107">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="6ae4c-107">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="6ae4c-108">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="6ae4c-108">Resource type</span></span></param>
        <param name="tags"><span data-ttu-id="6ae4c-109">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="6ae4c-109">Resource tags</span></span></param>
        <param name="provisioningState"><span data-ttu-id="6ae4c-110">Der Bereitstellungsstatus des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-110">the provisioning status of the Data Lake Analytics account.</span></span> <span data-ttu-id="6ae4c-111">Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-111">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span></param>
        <param name="state"><span data-ttu-id="6ae4c-112">der Status des Data Lake Analytics-Kontos.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-112">the state of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="6ae4c-113">Folgende Werte sind möglich: "Aktiv", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-113">Possible values include: 'Active', 'Suspended'</span></span></param>
        <param name="creationTime"><span data-ttu-id="6ae4c-114">die Erstellungszeit des Kontos.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-114">the account creation time.</span></span></param>
        <param name="lastModifiedTime"><span data-ttu-id="6ae4c-115">Zeitpunkt der letzten Änderung des Kontos.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-115">the account last modified time.</span></span></param>
        <param name="endpoint"><span data-ttu-id="6ae4c-116">der vollständige CName-Endpunkt für dieses Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-116">the full CName endpoint for this account.</span></span></param>
        <param name="accountId"><span data-ttu-id="6ae4c-117">Der eindeutige Bezeichner, der diesen Data Lake Analytics-Konto zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-117">The unique identifier associated with this Data Lake Analytics account.</span></span></param>
        <param name="maxDegreeOfParallelism"><span data-ttu-id="6ae4c-118">die maximal unterstützte Grad an Parallelität für dieses Konto an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-118">the maximum supported degree of parallelism for this account.</span></span></param>
        <param name="queryStoreRetention"><span data-ttu-id="6ae4c-119">die Anzahl der Tage, an denen Metadaten Auftrag wird beibehalten.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-119">the number of days that job metadata is retained.</span></span></param>
        <param name="maxJobCount"><span data-ttu-id="6ae4c-120">die maximal unterstützte Aufträge unter dem Konto, die gleichzeitig ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-120">the maximum supported jobs running under the account at the same time.</span></span></param>
        <param name="systemMaxDegreeOfParallelism"><span data-ttu-id="6ae4c-121">maximal unterstützte Grad an Parallelität für dieses Konto, das den maximalen Wert der Parallelität beschränkt, die der Benutzer für das Konto festlegen kann systemdefinierten...</span><span class="sxs-lookup"><span data-stu-id="6ae4c-121">the system defined maximum supported degree of parallelism for this account, which restricts the maximum value of parallelism the user can set for the account..</span></span></param>
        <param name="systemMaxJobCount"><span data-ttu-id="6ae4c-122">die systemdefinierte maximale unterstützten Aufträge, die unter dem Konto ausgeführt werden, zur gleichen Zeit, die einschränkt, die maximale Anzahl der ausgeführten Aufträge, die der Benutzer für das Konto festlegen kann.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-122">the system defined maximum supported jobs running under the account at the same time, which restricts the maximum number of running jobs the user can set for the account.</span></span></param>
        <param name="storageAccounts"><span data-ttu-id="6ae4c-123">die Liste der Azure-Blob-Speicherkonten, die diesem Konto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-123">the list of Azure Blob storage accounts associated with this account.</span></span></param>
        <param name="newTier"><span data-ttu-id="6ae4c-124">die Verpflichtung-Ebene für den nächsten Monat.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-124">the commitment tier for the next month.</span></span>
            <span data-ttu-id="6ae4c-125">Folgende Werte sind möglich: "Nutzung", "Commitment_100AUHours", "Commitment_500AUHours", "Commitment_1000AUHours", "Commitment_5000AUHours", "Commitment_10000AUHours", "Commitment_50000AUHours", "Commitment_100000AUHours", "Commitment_500000AUHours"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-125">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span></param>
        <param name="currentTier"><span data-ttu-id="6ae4c-126">verwendet für den aktuellen Monat Verpflichtung-Ebene.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-126">the commitment tier in use for the current month.</span></span> <span data-ttu-id="6ae4c-127">Folgende Werte sind möglich: "Nutzung", "Commitment_100AUHours", "Commitment_500AUHours", "Commitment_1000AUHours", "Commitment_5000AUHours", "Commitment_10000AUHours", "Commitment_50000AUHours", "Commitment_100000AUHours", "Commitment_500000AUHours"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-127">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span></param>
        <param name="firewallState"><span data-ttu-id="6ae4c-128">Der aktuelle Status der IP-Adresse-Firewall für das Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-128">The current state of the IP address firewall for this Data Lake Analytics account.</span></span> <span data-ttu-id="6ae4c-129">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-129">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallAllowAzureIps"><span data-ttu-id="6ae4c-130">Der aktuelle Status des zulassen oder untersagen von IP-Adressen, die in Azure über die Firewall stammen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-130">The current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span>
            <span data-ttu-id="6ae4c-131">Wenn die Firewall deaktiviert ist, ist dies nicht erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-131">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="6ae4c-132">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-132">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="firewallRules"><span data-ttu-id="6ae4c-133">Die Liste der Firewallregeln, die mit diesem Data Lake Analytics-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-133">The list of firewall rules associated with this Data Lake Analytics account.</span></span></param>
        <param name="maxDegreeOfParallelismPerJob"><span data-ttu-id="6ae4c-134">die maximal unterstützte Grad an Parallelität pro Auftrag für dieses Konto an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-134">the maximum supported degree of parallelism per job for this account.</span></span></param>
        <param name="minPriorityPerJob"><span data-ttu-id="6ae4c-135">die kleinste unterstützte Priorität pro Auftrag für dieses Konto an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-135">the minimum supported priority per job for this account.</span></span></param>
        <param name="computePolicies"><span data-ttu-id="6ae4c-136">die Liste der Compute-Richtlinien in diesem Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-136">the list of compute policies to create in this account.</span></span></param>
        <summary>
            <span data-ttu-id="6ae4c-137">Initialisiert eine neue Instanz der DataLakeAnalyticsAccount-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-137">Initializes a new instance of the DataLakeAnalyticsAccount class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; AccountId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.AccountId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-138">Ruft den eindeutigen Bezeichner dieses Data Lake Analytics-Konto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-138">Gets the unique identifier associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputePolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; ComputePolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputePolicies As IList(Of ComputePolicyAccountCreateParameters)" />
      <MemberSignature Language="F#" Value="member this.ComputePolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ComputePolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.computePolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.ComputePolicyAccountCreateParameters&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-139">Ruft ab oder legt die Liste der Compute-Richtlinien in diesem Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-139">Gets or sets the list of compute policies to create in this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-140">Ruft die Erstellungszeit des Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-140">Gets the account creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; CurrentTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.CurrentTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.CurrentTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-141">Ruft die Verpflichtung-Ebene verwendet für den aktuellen Monat an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-141">Gets the commitment tier in use for the current month.</span></span> <span data-ttu-id="6ae4c-142">Folgende Werte sind möglich: "Nutzung", "Commitment_100AUHours", "Commitment_500AUHours", "Commitment_1000AUHours", "Commitment_5000AUHours", "Commitment_10000AUHours", "Commitment_50000AUHours", "Commitment_100000AUHours", "Commitment_500000AUHours"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-142">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; DataLakeStoreAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLakeStoreAccounts As IList(Of DataLakeStoreAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DataLakeStoreAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLakeStoreAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeStoreAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-143">Ruft ab oder legt die Liste der Data Lake-Speicherkonten, die diesem Konto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-143">Gets or sets the list of Data Lake storage accounts associated with this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDataLakeStoreAccount">
      <MemberSignature Language="C#" Value="public string DefaultDataLakeStoreAccount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultDataLakeStoreAccount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultDataLakeStoreAccount As String" />
      <MemberSignature Language="F#" Value="member this.DefaultDataLakeStoreAccount : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.DefaultDataLakeStoreAccount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultDataLakeStoreAccount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-144">Abrufen oder Festlegen der Standard Data Lake-Speicher-Konto, mit diesem Data Lake Analytics-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-144">Gets or sets the default data lake storage account associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoint">
      <MemberSignature Language="C#" Value="public string Endpoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Endpoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Endpoint As String" />
      <MemberSignature Language="F#" Value="member this.Endpoint : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Endpoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-145">Ruft den vollständigen CName-Endpunkt für dieses Konto an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-145">Gets the full CName endpoint for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallAllowAzureIps">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; FirewallAllowAzureIps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallAllowAzureIps As Nullable(Of FirewallAllowAzureIpsState)" />
      <MemberSignature Language="F#" Value="member this.FirewallAllowAzureIps : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallAllowAzureIps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallAllowAzureIps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallAllowAzureIpsState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-146">Ruft ab oder legt den aktuellen Zustand des zulassen oder untersagen von IP-Adressen, die in Azure über die Firewall stammen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-146">Gets or sets the current state of allowing or disallowing IPs originating within Azure through the firewall.</span></span> <span data-ttu-id="6ae4c-147">Wenn die Firewall deaktiviert ist, ist dies nicht erforderlich.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-147">If the firewall is disabled, this is not enforced.</span></span> <span data-ttu-id="6ae4c-148">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-148">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallRules As IList(Of FirewallRule)" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-149">Ruft ab oder legt die Liste der Firewallregeln, die mit diesem Data Lake Analytics-Konto verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-149">Gets or sets the list of firewall rules associated with this Data Lake Analytics account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; FirewallState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberSignature Language="VB.NET" Value="Public Property FirewallState As Nullable(Of FirewallState)" />
      <MemberSignature Language="F#" Value="member this.FirewallState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.FirewallState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.firewallState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.FirewallState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-150">Ruft ab oder legt den aktuellen Status der IP-Adresse-Firewall für das Data Lake Analytics-Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-150">Gets or sets the current state of the IP address firewall for this Data Lake Analytics account.</span></span> <span data-ttu-id="6ae4c-151">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-151">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.LastModifiedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-152">Ruft die Uhrzeit der letzten Änderung des Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-152">Gets the account last modified time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-153">Ruft ab oder legt die maximale unterstützten Grad an Parallelität für dieses Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-153">Gets or sets the maximum supported degree of parallelism for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxDegreeOfParallelismPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxDegreeOfParallelismPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxDegreeOfParallelismPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxDegreeOfParallelismPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxDegreeOfParallelismPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxDegreeOfParallelismPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-154">Ruft ab oder legt die maximale unterstützten Grad an Parallelität pro Auftrag für dieses Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-154">Gets or sets the maximum supported degree of parallelism per job for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxJobCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxJobCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-155">Ruft ab oder legt die maximale unterstützten Aufträge unter dem Konto zur gleichen Zeit ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-155">Gets or sets the maximum supported jobs running under the account at the same time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinPriorityPerJob">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinPriorityPerJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinPriorityPerJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberSignature Language="VB.NET" Value="Public Property MinPriorityPerJob As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinPriorityPerJob : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.MinPriorityPerJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.minPriorityPerJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-156">Ruft ab oder legt die minimalen unterstützten Priorität pro Auftrag für dieses Konto.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-156">Gets or sets the minimum supported priority per job for this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NewTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; NewTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberSignature Language="VB.NET" Value="Public Property NewTier As Nullable(Of TierType)" />
      <MemberSignature Language="F#" Value="member this.NewTier : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.NewTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.newTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.TierType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-157">Ruft ab oder legt die Verpflichtung-Ebene für den nächsten Monat.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-157">Gets or sets the commitment tier for the next month.</span></span> <span data-ttu-id="6ae4c-158">Folgende Werte sind möglich: "Nutzung", "Commitment_100AUHours", "Commitment_500AUHours", "Commitment_1000AUHours", "Commitment_5000AUHours", "Commitment_10000AUHours", "Commitment_50000AUHours", "Commitment_100000AUHours", "Commitment_500000AUHours"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-158">Possible values include: 'Consumption', 'Commitment_100AUHours', 'Commitment_500AUHours', 'Commitment_1000AUHours', 'Commitment_5000AUHours', 'Commitment_10000AUHours', 'Commitment_50000AUHours', 'Commitment_100000AUHours', 'Commitment_500000AUHours'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of DataLakeAnalyticsAccountStatus)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-159">Ruft den Bereitstellungsstatus des Data Lake Analytics-Kontos an.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-159">Gets the provisioning status of the Data Lake Analytics account.</span></span>
            <span data-ttu-id="6ae4c-160">Folgende Werte sind möglich: "Fehlgeschlagen", "Erstellen", "Wird ausgeführt", "Erfolgreich abgeschlossen", "Patchen", "Angehalten", "Fortsetzen", "Löschen", "Deleted"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-160">Possible values include: 'Failed', 'Creating', 'Running', 'Succeeded', 'Patching', 'Suspending', 'Resuming', 'Deleting', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStoreRetention">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; QueryStoreRetention { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; QueryStoreRetention" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberSignature Language="VB.NET" Value="Public Property QueryStoreRetention As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.QueryStoreRetention : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.QueryStoreRetention" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.queryStoreRetention")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-161">Ruft ab oder legt sie fest, die die Anzahl der Tage, an denen Metadaten Auftrag aufbewahrt wird.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-161">Gets or sets the number of days that job metadata is retained.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of DataLakeAnalyticsAccountState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccountState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-162">Ruft den Status des Data Lake Analytics-Kontos ab.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-162">Gets the state of the Data Lake Analytics account.</span></span> <span data-ttu-id="6ae4c-163">Folgende Werte sind möglich: "Aktiv", "Angehalten"</span><span class="sxs-lookup"><span data-stu-id="6ae4c-163">Possible values include: 'Active', 'Suspended'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccountInfo)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.StorageAccountInfo&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-164">Ruft ab oder legt die Liste der Azure-Blob-Speicherkonten, die diesem Konto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-164">Gets or sets the list of Azure Blob storage accounts associated with this account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxDegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxDegreeOfParallelism { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxDegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxDegreeOfParallelism : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxDegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxDegreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-165">Ruft den vom System definierte maximale unterstützten Grad an Parallelität für dieses Konto, das den maximalen Wert der Parallelität beschränkt, die der Benutzer für das Konto festlegen kann...</span><span class="sxs-lookup"><span data-stu-id="6ae4c-165">Gets the system defined maximum supported degree of parallelism for this account, which restricts the maximum value of parallelism the user can set for the account..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SystemMaxJobCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SystemMaxJobCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SystemMaxJobCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SystemMaxJobCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SystemMaxJobCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.SystemMaxJobCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.systemMaxJobCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-166">Ruft das System definierte maximale unterstützten Aufträge, die unter dem Konto ausgeführt wird, zur gleichen Zeit, die einschränkt, die maximale Anzahl der ausgeführten Aufträge des Benutzers für das Konto festlegen können.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-166">Gets the system defined maximum supported jobs running under the account at the same time, which restricts the maximum number of running jobs the user can set for the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.DataLakeAnalyticsAccount.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="dataLakeAnalyticsAccount.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6ae4c-167">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6ae4c-167">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6ae4c-168">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6ae4c-168">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>