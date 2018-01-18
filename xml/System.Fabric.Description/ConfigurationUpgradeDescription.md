<Type Name="ConfigurationUpgradeDescription" FullName="System.Fabric.Description.ConfigurationUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ConfigurationUpgradeDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="7d1e5-101">Stellt eine Klasse zum Kapseln von Parametern, die einen Service Fabric-clusterupgrade Konfiguration beschreibt.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-101">Represents a class to encapsulate parameters describing a Service Fabric cluster configuration upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigurationUpgradeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationUpgradeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ConfigurationUpgradeDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.ConfigurationUpgradeDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterConfiguration">
      <MemberSignature Language="C#" Value="public string ClusterConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClusterConfiguration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.ClusterConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterConfiguration As String" />
      <MemberSignature Language="F#" Value="member this.ClusterConfiguration : string" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.ClusterConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7d1e5-103">Dies ist die Clusterkonfiguration, die angewendet werden, um Cluster.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-103">This is the cluster configuration that will be applied to cluster.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-104">Ruft ab oder legt die Zeitspanne zwischen den versuchen, eine integritätsprüfung ausführen, wenn die Anwendung oder der Cluster nicht fehlerfrei ist.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-104">Gets or sets the length of time between attempts to perform a health check if the application or cluster is not healthy.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-105">Die Länge der Zeit zwischen den versuchen, eine integritätsprüfungen auszuführen wird überprüft, ob die Anwendung oder der Cluster nicht fehlerfrei ist.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-105">The length of time between attempts to perform a health checks if the application or cluster is not healthy.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="7d1e5-106">Um eine Wiederholung Systemdiagnose zu verhindern, legen die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> Eigenschaftswert an <see cref="F:System.TimeSpan.Zero" />.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-106">To prevent a retry of the health check, set the <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> property value to <see cref="F:System.TimeSpan.Zero" />.</span></span> <span data-ttu-id="7d1e5-107">Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-107">The default is <see cref="F:System.TimeSpan.Zero" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckStableDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-108">Ruft ab oder legt die Länge der Zeit fest, die die Anwendung oder ein Cluster muss fehlerfrei, bevor die integritätsprüfung erfolgreich ist, und das Upgrade durchgeführt, um die nächste Domäne aktualisieren wird.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-108">Gets or sets the length of time that the application or cluster must remain healthy before the health check passes and the upgrade proceeds to the next Upgrade Domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-109">Die Zeitdauer, dass die Anwendung oder der Cluster fehlerfrei bleiben muss.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-109">The length of time that the application or cluster must remain healthy.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.HealthCheckWaitDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-110">Ruft ab oder legt die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Starten des Health Check-Prozesses.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-110">Gets or sets the length of time to wait after completing an upgrade domain before starting the health check process.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-111">Die Länge der Wartezeit nach Abschluss einer upgradedomäne, bevor der Prozess starten die Integrität überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-111">The length of time to wait after completing an upgrade domain before starting the health checks process.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="7d1e5-112">Eine unendliche Wartezeit für die integritätsprüfung durchgeführt werden soll, legen die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" /> Eigenschaftswert an <see cref="F:System.TimeSpan.Zero" />.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-112">To use an infinite wait for the health check, set the <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" /> property value to <see cref="F:System.TimeSpan.Zero" />.</span></span> <span data-ttu-id="7d1e5-113">Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-113">The default is <see cref="F:System.TimeSpan.Zero" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-114">Ruft ab oder legt den maximal zulässigen Prozentsatz Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-114">Gets or sets the maximum allowed percentage of nodes health degradation allowed during cluster upgrades.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-115">Die maximal zulässige Prozentsatz der Verringerung der Delta-Integrität.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-115">The maximum allowed percentage of delta health degradation.</span></span> <span data-ttu-id="7d1e5-116">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-116">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="7d1e5-117">Das Delta wird zwischen den Status der Knoten am Anfang des Upgrades und den Status der Knoten zum Zeitpunkt der Integritätsbewertung gemessen.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-117">The delta is measured between the state of the nodes at the beginning of upgrade and the state of the nodes at the time of the health evaluation.</span></span> <span data-ttu-id="7d1e5-118">Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-118">The check is performed after every upgrade domain upgrade completion to make sure the global state of the cluster is within tolerated limits.</span></span> <span data-ttu-id="7d1e5-119">Der Standardwert ist 10 %.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-119">The default value is 10%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="7d1e5-120">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-120">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyApplications">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyApplications { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyApplications" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyApplications" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyApplications As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyApplications : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyApplications" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-121">Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen aus dem <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-121">Gets the maximum allowed percentage of unhealthy applications from the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-122">Die maximal zulässige Prozentsatz fehlerhafter Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-122">The maximum allowed percentage of unhealthy applications.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-123">Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Knoten.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-123">Gets or sets the maximum allowed percentage of unhealthy nodes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-124">Die maximal zulässige Prozentsatz fehlerhafter Knoten.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-124">The maximum allowed percentage of unhealthy nodes.</span></span> <span data-ttu-id="7d1e5-125">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-125">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks>
          <para>
            <span data-ttu-id="7d1e5-126">Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Knoten, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-126">The percentage represents the maximum tolerated percentage of nodes that can be unhealthy before the cluster is considered in error.</span></span> <span data-ttu-id="7d1e5-127">Wird der Prozentsatz eingehalten, gibt es aber mindestens einen fehlerhaften Knoten, wird die Integrität als „Warning“ ausgewertet.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-127">If the percentage is respected but there is at least one unhealthy node, the health is evaluated as Warning.</span></span>
            <span data-ttu-id="7d1e5-128">Dies wird durch Dividieren der Anzahl der fehlerhaften Knoten über die Gesamtanzahl der Knoten im Cluster berechnet.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-128">This is calculated by dividing the number of unhealthy nodes over the total number of nodes in the cluster.</span></span>
            <span data-ttu-id="7d1e5-129">Die Berechnung wird aufgerundet, um einen Fehler auf einer kleinen Anzahl von Knoten zu tolerieren.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-129">The computation rounds up to tolerate one failure on small numbers of nodes.</span></span> <span data-ttu-id="7d1e5-130">Standardprozentsatz : null.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-130">Default percentage: zero.</span></span>
            </para>
          <para><span data-ttu-id="7d1e5-131">Beim Konfigurieren dieses Prozentsatzes muss berücksichtigt werden, dass in großen Clustern immer einige Knoten inaktiv oder aufgrund von Wartungsarbeiten nicht verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-131">In large clusters, some nodes will always be down or out for repairs, so this percentage should be configured to tolerate that.</span></span></para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="7d1e5-132">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-132">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-133">Ruft ab oder legt die maximal zulässige Prozentsatz upgradedomäne Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-133">Gets or sets the maximum allowed percentage of upgrade domain nodes health degradation allowed during cluster upgrades.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-134">Die maximal zulässige Prozentsatz upgradedomäne Delta Integrität Beeinträchtigung.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-134">The maximum allowed percentage of upgrade domain delta health degradation.</span></span> <span data-ttu-id="7d1e5-135">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-135">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="7d1e5-136">Das Delta wird zwischen den Status der Upgradedomänenknoten am Anfang des Upgrades und den Status der Upgradedomänenknoten zum Zeitpunkt der Integritätsbewertung gemessen.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-136">The delta is measured between the state of the upgrade domain nodes at the beginning of upgrade and the state of the upgrade domain nodes at the time of the health evaluation.</span></span> <span data-ttu-id="7d1e5-137">Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne für alle abgeschlossenen Upgradedomänen durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-137">The check is performed after every upgrade domain upgrade completion for all completed upgrade domains to make sure the state of the upgrade domains is within tolerated limits.</span></span> <span data-ttu-id="7d1e5-138">Der Standardwert ist 15 %.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-138">The default value is 15%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="7d1e5-139">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-139">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ConfigurationUpgradeDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="configurationUpgradeDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7d1e5-140">Ruft eine Zeichenfolgendarstellung der ConfigurationUpgradeDescription ab.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-140">Gets a string representation of the ConfigurationUpgradeDescription.</span></span>
            </summary>
        <returns><span data-ttu-id="7d1e5-141">Eine Zeichenfolgendarstellung der ConfigurationUpgradeDescription.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-141">A string representation of the ConfigurationUpgradeDescription.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeDomainTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-142">Ruft ab oder legt das Timeout für die upgradedomäne.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-142">Gets or sets the timeout for the upgrade domain.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-143">Das Timeout für die upgradedomäne.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-143">The timeout for the upgrade domain.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="7d1e5-144">Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</span><span class="sxs-lookup"><span data-stu-id="7d1e5-144">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.ConfigurationUpgradeDescription.UpgradeTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="7d1e5-145">Ruft ab oder legt die timeoutgesamtwert für das Upgrade.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-145">Gets or sets the upgrade timeout.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7d1e5-146">Der timeoutgesamtwert für das Upgrade.</span><span class="sxs-lookup"><span data-stu-id="7d1e5-146">The upgrade timeout.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="7d1e5-147">Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</span><span class="sxs-lookup"><span data-stu-id="7d1e5-147">The default is TimeSpan.FromSeconds(uint.MaxValue).</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>