<Type Name="MonitoredRollingFabricUpgradePolicyDescription" FullName="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public sealed class MonitoredRollingFabricUpgradePolicyDescription : System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit MonitoredRollingFabricUpgradePolicyDescription extends System.Fabric.Description.MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MonitoredRollingFabricUpgradePolicyDescription&#xA;Inherits MonitoredRollingUpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type MonitoredRollingFabricUpgradePolicyDescription = class&#xA;    inherit MonitoredRollingUpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.MonitoredRollingUpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1864d-101">Beschreibt das Verhalten beim Ausführen einer Cluster-Upgrades verwenden.</span><span class="sxs-lookup"><span data-stu-id="1864d-101">Describes the behavior to use when performing a cluster upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MonitoredRollingFabricUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1864d-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1864d-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1864d-103">Abrufen oder Festlegen der Anwendungsintegrität Richtlinien verwendet, um die Integrität von Anwendungen als Teil der integritätsauswertung Cluster ausgewertet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1864d-103">Gets or sets the application health policies used to evaluate the applications health as part of the cluster health evaluation.</span></span> 
            </summary>
        <value><span data-ttu-id="1864d-104">Die Integritätsrichtlinien für die Anwendung verwendet, um den Zustand des angegebenen auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="1864d-104">The application health policies used to evaluate the health of the specified applications.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="1864d-105">Während des Cluster-Upgrades wird die Integrität des Clusters ausgewertet, um festzustellen, ob der Cluster weiterhin fehlerfrei ist.</span><span class="sxs-lookup"><span data-stu-id="1864d-105">During cluster upgrade, the health of the cluster is evaluated to determine whether the cluster is still healthy.</span></span> <span data-ttu-id="1864d-106">Im Rahmen der integritätsauswertung Cluster sind alle Anwendungen ausgewertet und in den Clusterzustand aggregiert.</span><span class="sxs-lookup"><span data-stu-id="1864d-106">As part of the cluster health evaluation, all applications are evaluated and aggregated in the cluster health.</span></span>
            <span data-ttu-id="1864d-107">Die Anwendung Integrität Richtlinie Zuordnung wird zum Auswerten der Anwendungen im Rahmen der Auswertung der Cluster verwendet.</span><span class="sxs-lookup"><span data-stu-id="1864d-107">The application health policy map is used to evaluate the applications as part of the cluster evaluation.</span></span>
            </para>
          <para>
            <span data-ttu-id="1864d-108">Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand der betreffenden Anwendung auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="1864d-108">Each entry specifies as key the application name and as value an <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health of that application.</span></span></para>
          <para>
            <span data-ttu-id="1864d-109">Wenn eine Anwendung nicht in der Zuordnung angegeben wird, wird die ApplicationHealthPolicy gefunden, die im Anwendungsmanifest für die Auswertung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="1864d-109">If an application is not specified in the map, the ApplicationHealthPolicy found in the application manifest will be used for evaluation.</span></span> </para>
          <para>
            <span data-ttu-id="1864d-110">Benutzerdefinierter anwendungsintegritätsrichtlinien werden auch zum Auswerten der clusterintegrität während des Upgrades über <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> oder <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="1864d-110">The custom application health policies are also used to evaluate cluster health during upgrade, through <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> or <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
          <para>
            <span data-ttu-id="1864d-111">Die Zuordnung ist standardmäßig leer.</span><span class="sxs-lookup"><span data-stu-id="1864d-111">The map is empty by default.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public bool EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Boolean" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : bool with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.EnableDeltaHealthEvaluation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1864d-112">Ruft ab oder legt ein Flag, das angibt, ob die Delta-Evaluation aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1864d-112">Gets or sets a flag indicating whether delta evaluation is enabled.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="1864d-113"><languageKeyword>"true"</languageKeyword> bei der Delta-integritätsauswertung aktiviert ist; <languageKeyword>"false"</languageKeyword> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="1864d-113"><languageKeyword>true</languageKeyword> when delta health evaluation is enabled; <languageKeyword>false</languageKeyword> otherwise.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1864d-114">Bei der Delta-Evaluation aktiviert ist, wird sichergestellt, dass die integritätsauswertung für den Cluster, dass die Beeinträchtigung der Integrität Hinsicht-Beschränkung toleriert werden global auf alle Knoten und pro jede upgradedomäne, der ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="1864d-114">When delta evaluation is enabled, the cluster health evaluation ensures that the degradation of health respects tolerated limits, both globally, across all nodes, and per each upgrade domain that is evaluated.</span></span> <span data-ttu-id="1864d-115">Die zulässigen Schwellenwerte werden in angegeben <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="1864d-115">The tolerated thresholds are specified in <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</span></span></para>
          <para><span data-ttu-id="1864d-116">Delta-Auswertung ist standardmäßig deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="1864d-116">Delta evaluation is disabled by default.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1864d-117">Abrufen oder festlegen die Integritätsrichtlinie zu verwendende hochleistungsfähiger Integrität für einen Cluster mit einem Upgrade überprüft.</span><span class="sxs-lookup"><span data-stu-id="1864d-117">Gets or sets the health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1864d-118">Beim Ausführen der Integrität zu verwendende Integritätsrichtlinie überprüft ein Cluster aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="1864d-118">The health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterUpgradeHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1864d-119">Abrufen oder festlegen die Delta-Integritätsrichtlinie zu verwendende hochleistungsfähiger Integrität für einen Cluster mit einem Upgrade überprüft.</span><span class="sxs-lookup"><span data-stu-id="1864d-119">Gets or sets the delta health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1864d-120">Die Delta-Integritätsrichtlinie beim Ausführen der Integrität zu verwendenden überprüft anhand eines Clusters aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="1864d-120">The delta health policy to use when performing health checks against an upgrading cluster.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="1864d-121">Die Upgrade Integritätsrichtlinie wird verwendet, wenn <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> festgelegt ist, um <languageKeyword>"true"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="1864d-121">The upgrade health policy is used when <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> is set to <languageKeyword>true</languageKeyword>.</span></span> <span data-ttu-id="1864d-122">Delta-Auswertung ist standardmäßig deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="1864d-122">Delta evaluation is disabled by default.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>