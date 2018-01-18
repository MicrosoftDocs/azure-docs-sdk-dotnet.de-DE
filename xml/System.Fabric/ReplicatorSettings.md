<Type Name="ReplicatorSettings" FullName="System.Fabric.ReplicatorSettings">
  <TypeSignature Language="C#" Value="public sealed class ReplicatorSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicatorSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ReplicatorSettings" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicatorSettings" />
  <TypeSignature Language="F#" Value="type ReplicatorSettings = class" />
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
      <para><span data-ttu-id="6d5b2-101">Ermöglicht ein zustandsbehaftetes Replikat so konfigurieren Sie die <see cref="T:System.Fabric.FabricReplicator" /> auch über die Erstellung <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-101">Allows a stateful replica to configure the <see cref="T:System.Fabric.FabricReplicator" /> when creating it via <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicatorSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.ReplicatorSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-102">Initializes a new instance of the <see cref="T:System.Fabric.ReplicatorSettings" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchAcknowledgementInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; BatchAcknowledgementInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; BatchAcknowledgementInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchAcknowledgementInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.BatchAcknowledgementInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-103">Ruft ab oder legt die Zeitspanne, die der Replikator nach dem Empfang eines Vorgangs vor dem Zurücksenden einer Bestätigung wartet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-103">Gets or sets the amount of time that the replicator waits after receiving an operation before sending back an acknowledgment.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-104">Die Zeitspanne, die der Replikator nach dem Empfang eines Vorgangs vor dem Zurücksenden einer Bestätigung wartet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-104">The amount of time that the replicator waits after receiving an operation before sending back an acknowledgment.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-105">Andere Vorgänge empfangen und während dieses Zeitraums bestätigt haben ihre Bestätigungen wieder in einer einzelnen Nachricht gesendet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-105">Other operations received and acknowledged during this time period will have their acknowledgments sent back in a single message.</span></span></para>
          <para><span data-ttu-id="6d5b2-106">Erhöhen der <see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> Wert verringert die Latenz der einzelnen Replikationsvorgängen jedoch erhöht den Durchsatz der Replikator.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-106">Increasing the <see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> value decreases latency of individual replication operations but increases throughput of the replicator.</span></span></para>
          <para><span data-ttu-id="6d5b2-107">Standardwert ist 0,05 Sekunden (50 Millisekunden)</span><span class="sxs-lookup"><span data-stu-id="6d5b2-107">Default value is 0.05 Seconds (50 milliseconds)</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-108">Ruft ab oder legt die Anfangsgröße der Kopie Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-108">Gets or sets the initial size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-109">Die Anfangsgröße der Vorgangswarteschlange Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-109">The initial size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-110">Der Standardwert ist 64.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-110">The default value is 64.</span></span> <span data-ttu-id="6d5b2-111">Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-111">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-112">Definiert die anfängliche Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.The Einheit hier ist die Anzahl der Vorgänge in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-112">Defines the initial size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.The unit here is the number of operations in the queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-113">Die Anfangsgröße der primären Replikation Vorgangswarteschlange innerhalb<see cref="T:System.Fabric.FabricReplicator" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-113">The initial size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" /></span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-114">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primären</span><span class="sxs-lookup"><span data-stu-id="6d5b2-114">This setting is specific to the Replicator when the role of the service is Primary</span></span></para>
          <para><span data-ttu-id="6d5b2-115">Der Standardwert ist 64.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-115">The default value is 64.</span></span>  <span data-ttu-id="6d5b2-116">Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-116">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-117">Ruft ab oder legt die Anfangsgröße der Größe der Replikation.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-117">Gets or sets the initial size of the replication queue size.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-118">Die Anfangsgröße der Größe der Replikation.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-118">The initial size of the replication queue size.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="InitialSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; InitialSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property InitialSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.InitialSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-119">Definiert die anfängliche Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="6d5b2-119">Defines the initial size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-120">Die Anfangsgröße der sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-120">The initial size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span> <span data-ttu-id="6d5b2-121">Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange</span><span class="sxs-lookup"><span data-stu-id="6d5b2-121">The unit here is the number of operations in the queue</span></span> </para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-122">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/Leerlauf</span><span class="sxs-lookup"><span data-stu-id="6d5b2-122">This setting is specific to the Replicator when the role of the service is Secondary/Idle</span></span></para>
          <para><span data-ttu-id="6d5b2-123">Der Standardwert ist 64.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-123">The default value is 64.</span></span>  <span data-ttu-id="6d5b2-124">Beachten Sie, dass die Werte für diesen Parameter eine Potenz von 2 sein müssen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-124">Note that values for this parameter must be a power of 2.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadFrom">
      <MemberSignature Language="C#" Value="public static System.Fabric.ReplicatorSettings LoadFrom (System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Fabric.ReplicatorSettings LoadFrom(class System.Fabric.CodePackageActivationContext codePackageActivationContext, string configPackageName, string sectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ReplicatorSettings.LoadFrom(System.Fabric.CodePackageActivationContext,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member LoadFrom : System.Fabric.CodePackageActivationContext * string * string -&gt; System.Fabric.ReplicatorSettings" Usage="System.Fabric.ReplicatorSettings.LoadFrom (codePackageActivationContext, configPackageName, sectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codePackageActivationContext" Type="System.Fabric.CodePackageActivationContext" />
        <Parameter Name="configPackageName" Type="System.String" />
        <Parameter Name="sectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codePackageActivationContext">
          <para><span data-ttu-id="6d5b2-125">Die aktuelle Codepaket-Aktivierungskontext<see cref="T:System.Fabric.CodePackageActivationContext" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-125">The current code package activation context <see cref="T:System.Fabric.CodePackageActivationContext" /></span></span></para>
        </param>
        <param name="configPackageName">
          <para><span data-ttu-id="6d5b2-126">Die aktuelle Konfiguration Paketname</span><span class="sxs-lookup"><span data-stu-id="6d5b2-126">The current configuration package name</span></span></para>
        </param>
        <param name="sectionName">
          <para><span data-ttu-id="6d5b2-127">Im Abschnitt in der Konfigurationsdatei, die alle Replikator Einstellungen definiert.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-127">The section within the configuration file that defines all the replicator settings</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="6d5b2-128">Lädt die <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt aus den Einstellungen der Dienstkonfigurationsdatei.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-128">Loads the <see cref="T:System.Fabric.ReplicatorSettings" /> object from the service configuration settings file.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="6d5b2-129">Das geladene <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt aus den Einstellungen der Dienstkonfigurationsdatei</span><span class="sxs-lookup"><span data-stu-id="6d5b2-129">The loaded <see cref="T:System.Fabric.ReplicatorSettings" /> object from the service configuration settings file</span></span></para>
        </returns>
        <remarks>
          <para> <span data-ttu-id="6d5b2-130">Die Einstellungen Konfigurationsdatei ("Settings.xml") in den Konfigurationsordner Dienst in der Regel enthält die Replicator-Einstellungen, die erforderlich ist, übergeben die <see cref="T:System.Fabric.ReplicatorSettings" /> -Objekt an die <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> Methode.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-130">The configuration settings file (settings.xml) within the service configuration folder generally contains all the replicator settings that is needed to pass in the <see cref="T:System.Fabric.ReplicatorSettings" /> object to the <see cref="M:System.Fabric.IStatefulServicePartition.CreateReplicator(System.Fabric.IStateProvider,System.Fabric.ReplicatorSettings)" /> method.</span></span> <span data-ttu-id="6d5b2-131">In der Regel bleibt auf den dienstautor, lesen Sie die Datei "Settings.xml", analysieren Sie die Werte aus, und erstellen entsprechend der <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-131">Typically, the onus is on the service author to read the settings.xml file, parse the values and appropriately construct the <see cref="T:System.Fabric.ReplicatorSettings" /> object.</span></span></para>
          <para><span data-ttu-id="6d5b2-132">Mit der aktuellen Hilfsmethode kann den oben aufgeführten Vorgang dienstautor umgangen werden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-132">With the current helper method, the service author can bypass the above process.</span></span></para>
          <para><span data-ttu-id="6d5b2-133">Es folgen die Namen der Parameter, die in der Dienstkonfiguration "settings.xml" von Windows Fabric, um die oben genannten Analyse automatisch erkannt werden bereitgestellt werden sollten:</span><span class="sxs-lookup"><span data-stu-id="6d5b2-133">The following are the parameter names that should be provided in the service configuration “settings.xml”, to be recognizable by windows fabric to perform the above parsing automatically:</span></span></para>
          <list type="number">
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-134">BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> Wert in Sekunden</span><span class="sxs-lookup"><span data-stu-id="6d5b2-134">BatchAcknowledgementInterval –<see cref="P:System.Fabric.ReplicatorSettings.BatchAcknowledgementInterval" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-135">InitialCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-135">InitialCopyQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialCopyQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-136">MaxCopyQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-136">MaxCopyQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-137">MaxReplicationMessageSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-137">MaxReplicationMessageSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-138">RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" /> Wert in Sekunden</span><span class="sxs-lookup"><span data-stu-id="6d5b2-138">RetryInterval -<see cref="P:System.Fabric.ReplicatorSettings.RetryInterval" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-139">RequireServiceAck-<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-139">RequireServiceAck -<see cref="P:System.Fabric.ReplicatorSettings.RequireServiceAck" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-140">ReplicatorAddress oder ReplicatorEndpoint – sollten ReplicatorAddress des Formulars IPort sein.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-140">ReplicatorAddress or ReplicatorEndpoint – ReplicatorAddress should be of the form IPort.</span></span> <span data-ttu-id="6d5b2-141">ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-141">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-142">ReplicatorListenAddress oder ReplicatorEndpoint – sollten ReplicatorListenAddress des Formulars IPort sein.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-142">ReplicatorListenAddress or ReplicatorEndpoint – ReplicatorListenAddress should be of the form IPort.</span></span> <span data-ttu-id="6d5b2-143">ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-143">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-144">ReplicatorPublishAddress oder ReplicatorEndpoint – sollten ReplicatorPublishAddress des Formulars IPort sein.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-144">ReplicatorPublishAddress or ReplicatorEndpoint – ReplicatorPublishAddress should be of the form IPort.</span></span> <span data-ttu-id="6d5b2-145">ReplicatorEndpoint muss eine gültigen Endpunkt Dienstressource von im Dienstmanifest verweisen-<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-145">ReplicatorEndpoint must reference a valid service endpoint resource from the service manifest -<see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-146">SecondaryClearAcknowledgedOperations-<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-146">SecondaryClearAcknowledgedOperations -<see cref="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-147">PrimaryWaitForPendingQuorumsTimeout - <see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" /> Wert in Sekunden</span><span class="sxs-lookup"><span data-stu-id="6d5b2-147">PrimaryWaitForPendingQuorumsTimeout - <see cref="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" /> value in seconds</span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-148">UseStreamFaultsAndEndOfStreamOperationAck-<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-148">UseStreamFaultsAndEndOfStreamOperationAck -<see cref="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-149">InitialPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-149">InitialPrimaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialPrimaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-150">InitialSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-150">InitialSecondaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.InitialSecondaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-151">MaxPrimaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-151">MaxPrimaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-152">MaxSecondaryReplicationQueueSize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-152">MaxSecondaryReplicationQueueSize -<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-153">MaxPrimaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-153">MaxPrimaryReplicationQueueMemorySize -<see cref="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" /></span></span></para>
              </description>
            </item>
            <item>
              <description>
                <para><span data-ttu-id="6d5b2-154">MaxSecondaryReplicationQueueMemorySize-<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-154">MaxSecondaryReplicationQueueMemorySize -<see cref="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" /></span></span></para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxCopyQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxCopyQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxCopyQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxCopyQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxCopyQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxCopyQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-155">Ruft ab oder legt die maximale Größe der Warteschlange Vorgang Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-155">Gets or sets the maximum size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-156">Die maximale Größe der Warteschlange Vorgang Kopie innerhalb <see cref="T:System.Fabric.FabricReplicator" />, das Kopie enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-156">The maximum size of the copy operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains copy <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-157">Wenn die Größe der Sendewarteschlange auf dem sekundären Server erreicht ist, werden Vorgänge in der primären Kopiewarteschlange gepuffert werden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-157">If this queue size is reached at the secondary, operations will be buffered in the Primary’s copy queue.</span></span> <span data-ttu-id="6d5b2-158">Wenn diese Warteschlange auch voll ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-158">If that queue also fills, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="6d5b2-159">Der Standardwert ist 1024</span><span class="sxs-lookup"><span data-stu-id="6d5b2-159">The default value is 1024</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-160">Definiert die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="6d5b2-160">Defines the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-161">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-161">.</span></span> <span data-ttu-id="6d5b2-162">Gibt die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s hier die Einheit ist der virtuelle Arbeitsspeicherverbrauch der Warteschlange. Gibt <see cref="T:System.Int64" />.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-162">Returns the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s The unit here is the virtual memory consumption of the queue .Returns <see cref="T:System.Int64" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-163">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primär ist.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-163">This setting is specific to the Replicator when the role of the service is Primary.</span></span> <span data-ttu-id="6d5b2-164">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-164">The default value is 0.</span></span> <span data-ttu-id="6d5b2-165">Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="6d5b2-165">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPrimaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxPrimaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPrimaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxPrimaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxPrimaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-166">Definiert die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="6d5b2-166">Defines the maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-167">Die maximale Größe der primären Replikation Vorgangswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-167">The maximum size of the primary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span> <span data-ttu-id="6d5b2-168">Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-168">The unit here is the number of operations in the queue.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-169">Wenn diese Warteschlangengröße erreicht ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-169">If this queue size is reached, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="6d5b2-170">Der Standardwert ist 1024 Hinweis, der Werte für diesen Parameter muss eine Potenz von 2 sein.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-170">The default value is 1024 Note that values for this parameter must be a power of 2.</span></span></para>
          <para><span data-ttu-id="6d5b2-171">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts primären</span><span class="sxs-lookup"><span data-stu-id="6d5b2-171">This setting is specific to the Replicator when the role of the service is Primary</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationMessageSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationMessageSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationMessageSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationMessageSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationMessageSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationMessageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-172">Ruft ab oder legt die maximale Größe einer Nachricht, die über die Replicator übertragen werden können.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-172">Gets or sets the maximum size of a message that can be transmitted via the replicator.</span></span> <span data-ttu-id="6d5b2-173">Diese Nachrichten enthalten, kopieren Sie Nachrichten und Kontext Meldungen kopieren.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-173">These include replication messages, copy messages and copy context messages.</span></span> <span data-ttu-id="6d5b2-174">Die Einheit der Darstellung ist Bytes.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-174">The unit of representation is bytes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-175">Die maximale Größe einer Nachricht, die über die Replicator übertragen werden können.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-175">The maximum size of a message that can be transmitted via the replicator.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-176">Der Standardwert ist 50MB</span><span class="sxs-lookup"><span data-stu-id="6d5b2-176">The default value is 50MB</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-177">Ruft ab oder legt die maximale Größe für die Replikation Warteschlange Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-177">Gets or sets the maximum size for the replication queue memory.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-178">Die maximale Größe für die Replikation Warteschlange Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-178">The maximum size for the replication queue memory.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-179">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-179">The default value is 0.</span></span> <span data-ttu-id="6d5b2-180">Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="6d5b2-180">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-181">Ruft ab oder legt die maximale Größe für die Replikationswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-181">Gets or sets the maximum size for the replication queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-182">die maximale Größe für die Replikationswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-182">the maximum size for the replication queue.</span></span></para>
        </value>
        <remarks>
          <para />
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueMemorySize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueMemorySize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueMemorySize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueMemorySize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueMemorySize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-183">Definiert die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-183">Defines the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-184">Gibt die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-184">Returns the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s.</span></span> <span data-ttu-id="6d5b2-185">Die Einheit hier ist der virtuelle Arbeitsspeicherverbrauch der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-185">The unit here is the virtual memory consumption of the queue.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-186">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/im Leerlauf ist.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-186">This setting is specific to the Replicator when the role of the service is Secondary/Idle.</span></span> <span data-ttu-id="6d5b2-187">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-187">The default value is 0.</span></span> <span data-ttu-id="6d5b2-188">Dies bedeutet, dass kein Arbeitsspeicherlimit vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="6d5b2-188">This implies there is no memory limit</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSecondaryReplicationQueueSize">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; MaxSecondaryReplicationQueueSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSecondaryReplicationQueueSize As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.MaxSecondaryReplicationQueueSize : Nullable&lt;int64&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.MaxSecondaryReplicationQueueSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-189">Definiert die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s</span><span class="sxs-lookup"><span data-stu-id="6d5b2-189">Defines the maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-190">Die maximale Größe des sekundären Vorgang Replikationswarteschlange innerhalb <see cref="T:System.Fabric.FabricReplicator" />, die Replikation enthält <see cref="T:System.Fabric.IOperation" />s noch nicht gepumpt und vom Dienst verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-190">The maximum size of the secondary replication operation queue inside <see cref="T:System.Fabric.FabricReplicator" />, which contains replication <see cref="T:System.Fabric.IOperation" />s not yet pumped and processed by the service.</span></span> <span data-ttu-id="6d5b2-191">Die Einheit hier ist die Anzahl der Vorgänge in der Warteschlange</span><span class="sxs-lookup"><span data-stu-id="6d5b2-191">The unit here is the number of operations in the queue</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-192">Wenn diese Größe erreicht ist, werden Vorgänge in der primären Replikationswarteschlange gepuffert werden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-192">If this queue size is reached, operations will be buffered in the Primary’s replication queue.</span></span>  <span data-ttu-id="6d5b2-193">Wenn diese Warteschlange auch voll ist, wird angezeigt, die primäre beginnt <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> Ausnahmen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-193">If that queue also fills, then the Primary will begin seeing <see cref="F:System.Fabric.FabricErrorCode.ReplicationQueueFull" /> exceptions.</span></span></para>
          <para><span data-ttu-id="6d5b2-194">Der Standardwert ist 2048.Note, die Werte für diesen Parameter muss eine Potenz von 2 sein.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-194">The default value is 2048.Note that values for this parameter must be a power of 2.</span></span></para>
          <para><span data-ttu-id="6d5b2-195">Diese Einstellung bezieht sich auf Replikator, wenn die Rolle des Diensts Sekundär/Leerlauf</span><span class="sxs-lookup"><span data-stu-id="6d5b2-195">This setting is specific to the Replicator when the role of the service is Secondary/Idle</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryWaitForPendingQuorumsTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryWaitForPendingQuorumsTimeout As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.PrimaryWaitForPendingQuorumsTimeout : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.PrimaryWaitForPendingQuorumsTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-196">Definiert, wie lange der primäre Replikator wartet, für den Empfang von einem Quorum von Bestätigungen für alle ausstehenden Replikationsvorgänge vor der Verarbeitung einer Neukonfiguration-Anforderung, die potenziell führen die ausstehenden Replikationsvorgänge dazu "Abbrechen".</span><span class="sxs-lookup"><span data-stu-id="6d5b2-196">Defines how long the primary replicator waits for receiving a quorum of acknowledgments for any pending replication operations before processing a reconfiguration request, that could potentially result in ‘cancelling’ the pending replication operations.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-197">Wartet, bis der primäre Replikator ein Quorum von Bestätigungen für alle ausstehenden Replikationsvorgängen empfangen, wenn es eine Anforderung für den primären Replikator zum Verarbeiten einer Neukonfiguration liegt Zeitspanne <see cref="T:System.TimeSpan" />.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-197">Amount of time the primary replicator waits for receiving a quorum of acknowledgments for any pending replication operations when there is a request for the primary replicator to process a reconfiguration <see cref="T:System.TimeSpan" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-198">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-198">The default value is 0.</span></span> <span data-ttu-id="6d5b2-199">Dies bedeutet, dass für den Empfang von Quorum auf die ausstehende Replikationsvorgänge die Neukonfigurationen nach gewartet werden nicht.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-199">This implies that reconfigurations aren’t waited upon for receiving quorum on the pending replication operations.</span></span> <span data-ttu-id="6d5b2-200">Dies hilft beim Abschließen der Neukonfigurationen früher.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-200">This helps in completing reconfigurations sooner.</span></span> <span data-ttu-id="6d5b2-201">Beachten Sie, dass größere Werte für diesen Parameter möglicherweise langsamer Neukonfigurationen, Gleichzeichen längere dauern, um einen primären Failover führen können.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-201">Note that larger values for this parameter could potentially result in slower reconfigurations, implying longer durations to fail-over a primary.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorAddress" />
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
          <para><span data-ttu-id="6d5b2-202">Konfiguriert die Adresse, die bei der Kommunikation mit anderen Replikatoren dieser Replikator verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-202">Configures the address that this replicator will use when communicating with other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-203">Die Adresse, die bei der Kommunikation mit anderen Replikatoren dieser Replikator verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-203">The address that this replicator will use when communicating with other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-204">Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-204">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="6d5b2-205">Der Standardwert ist Localhost:0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-205">The default value is localhost:0.</span></span> <span data-ttu-id="6d5b2-206">Wenn Replikator innerhalb eines Containers ausgeführt wird, sollten Sie versuchen, das Einrichten <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /> und <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-206">If replicator is running inside a container, you should try setting up <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" /> and <see cref="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorListenAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorListenAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorListenAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorListenAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorListenAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorListenAddress" />
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
          <para><span data-ttu-id="6d5b2-207">Konfiguriert die abhöradresse, die diese Replikator zum Empfangen von Informationen aus anderen Replikatoren verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-207">Configures the listen address that this replicator will use to receieve information from other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-208">Die abhöradresse, die diese Replikator zum Empfangen von Informationen aus anderen Replikatoren verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-208">The listen address that this replicator will use to receive information from other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-209">Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-209">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="6d5b2-210">Der Standardwert ist Localhost:0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-210">The default value is localhost:0.</span></span> <span data-ttu-id="6d5b2-211">Hostname für abhöradresse kann aus abgerufen werden<see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-211">hostname for listen address can be obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ServiceListenAddress" /></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorPublishAddress">
      <MemberSignature Language="C#" Value="public string ReplicatorPublishAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicatorPublishAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicatorPublishAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicatorPublishAddress : string with get, set" Usage="System.Fabric.ReplicatorSettings.ReplicatorPublishAddress" />
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
          <para><span data-ttu-id="6d5b2-212">Konfiguriert die Publish-Adresse, die diese Replikator zum Senden von Informationen an andere Replikatoren verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-212">Configures the publish address that this replicator will use to send information to other Replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-213">Die Adresse der veröffentlichen, die diese Replikator zum Senden von Informationen an andere Replikatoren verwenden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-213">The publish address that this replicator will use to send information to other Replicators.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-214">Zeichenfolge wird als "Hostname:port", formatiert, in dem der Hostname FQDN oder IP-Adresse sein kann.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-214">String is formatted as “hostname:port”, where hostname can be FQDN or IP address.</span></span> <span data-ttu-id="6d5b2-215">Der Standardwert ist Localhost:0.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-215">The default value is localhost:0.</span></span> <span data-ttu-id="6d5b2-216">Hostname für veröffentlichen Adresse kann von abgerufen werden<see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></span><span class="sxs-lookup"><span data-stu-id="6d5b2-216">hostname for publish address can be obtained from <see cref="P:System.Fabric.CodePackageActivationContext.ServicePublishAddress" /></span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequireServiceAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RequireServiceAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RequireServiceAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberSignature Language="VB.NET" Value="Public Property RequireServiceAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RequireServiceAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RequireServiceAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-217">Verhindert, dass die optimistische Bestätigung von Vorgängen in nicht persistente Dienste durch das anfordern, die der Dienst ruft <see cref="M:System.Fabric.IOperation.Acknowledge" /> , bevor er den nächsten Vorgang ruft.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-217">Prevents the optimistic acknowledgment of operations in non-persistent services by requiring that the service calls <see cref="M:System.Fabric.IOperation.Acknowledge" /> before it pumps the next operation.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="6d5b2-218"><languageKeyword>"true"</languageKeyword> Wenn die vollständige Bestätigung von Vorgängen in nicht persistente Dienste; andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-218"><languageKeyword>true</languageKeyword> if the optimistic acknowledgment of operations in non-persistent services;otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-219">Nicht persistenter Dienste, die explizite Bestätigung erfordern können diese Eigenschaft auf "true" festlegen, um zu verhindern, dass der Vorgänge vom Replikator optimistische Bestätigung.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-219">Non-persistent services which require explicit acknowledgment can set this property to True in order to prevent optimistic acknowledgment of the operations by the Replicator.</span></span> <span data-ttu-id="6d5b2-220">Diese Einstellung wirkt sich nicht bei beständigen Diensten aus.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-220">This setting has no effect for persistent services.</span></span> </para>
          <para><span data-ttu-id="6d5b2-221">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-221">The default value is false.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetryInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetryInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetryInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.RetryInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-222">Definiert, wie lange der <see cref="T:System.Fabric.FabricReplicator" /> wartet, nachdem er überträgt eine Nachricht vom primären auf die sekundäre Datenbank für die sekundäre Datenbank zu bestätigen, dass er die Nachricht empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-222">Defines how long the <see cref="T:System.Fabric.FabricReplicator" /> waits after it transmits a message from the primary to the secondary for the secondary to acknowledge that it has received the message.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-223">Die benötigte Zeit die <see cref="T:System.Fabric.FabricReplicator" /> wartet, nachdem er überträgt eine Nachricht vom primären auf die sekundäre Datenbank für die sekundäre Datenbank zu bestätigen, dass er die Nachricht empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-223">The time needed the <see cref="T:System.Fabric.FabricReplicator" /> waits after it transmits a message from the primary to the secondary for the secondary to acknowledge that it has received the message.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-224">Empfangen einer Nachricht wird nicht unbedingt, dass die Nachricht verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-224">Receiving a message does not necessarily that the message has been processed.</span></span></para>
          <para><span data-ttu-id="6d5b2-225">Wenn dieser Zeitgeber überschritten wird, wird die Nachricht erneut übertragen.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-225">If this timer is exceeded, then the message is retransmitted.</span></span></para>
          <para><span data-ttu-id="6d5b2-226">Der Standardwert ist 5 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-226">The default value is 5 seconds.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryClearAcknowledgedOperations">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; SecondaryClearAcknowledgedOperations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryClearAcknowledgedOperations As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.SecondaryClearAcknowledgedOperations : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.SecondaryClearAcknowledgedOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-227">Vorgänge in der sekundären Replikator bleiben in der Regel in der Warteschlange, Catchup Replikate Lage sein, wenn sie mit einem primären Replikat höher gestuft ist.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-227">Typically, operations in the secondary replicator are kept in the queue to be able to catchup replicas if it is promoted to a primary.</span></span> <span data-ttu-id="6d5b2-228">Dieses Flag aktiviert ist gibt sekundären Replikator den Vorgang frei, sobald es vom Dienst für die bestätigt wird.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-228">With this flag enabled, the secondary replicator releases the operation as soon as it is acknowledged by the user service.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="6d5b2-229"><languageKeyword>"true"</languageKeyword> Wenn sekundäre Replikator den Vorgang frei, sobald er durch den Dienst für die bestätigte ist, andernfalls ist <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-229"><languageKeyword>true</languageKeyword> if the secondary replicator releases the operation as soon as it is acknowledged by the user service; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="6d5b2-230">Der Standardwert ist "false"</span><span class="sxs-lookup"><span data-stu-id="6d5b2-230">The default value is false</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityCredentials">
      <MemberSignature Language="C#" Value="public System.Fabric.SecurityCredentials SecurityCredentials { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.SecurityCredentials SecurityCredentials" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityCredentials As SecurityCredentials" />
      <MemberSignature Language="F#" Value="member this.SecurityCredentials : System.Fabric.SecurityCredentials with get, set" Usage="System.Fabric.ReplicatorSettings.SecurityCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.SecurityCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="6d5b2-231">Ermöglicht dem Dienst um Sicherheitsanmeldeinformationen für die Sicherung des Datenverkehrs zwischen Replikatoren zu definieren.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-231">Allows the service to define security credentials for securing the traffic between replicators.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="6d5b2-232">Der Dienst zum Definieren der Sicherheitsanmeldeinformationen für die Sicherung des Datenverkehrs zwischen Replikatoren.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-232">The service to define security credentials for securing the traffic between replicators.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseStreamFaultsAndEndOfStreamOperationAck">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberSignature Language="VB.NET" Value="Public Property UseStreamFaultsAndEndOfStreamOperationAck As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseStreamFaultsAndEndOfStreamOperationAck : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.ReplicatorSettings.UseStreamFaultsAndEndOfStreamOperationAck" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary><span data-ttu-id="6d5b2-233">Dies unterstützt die Service Fabric-Infrastruktur und ist nicht vorgesehen, direkt aus Ihrem Code verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6d5b2-233">This supports the Service Fabric infrastructure and is not meant to be used directly from your code.</span></span></summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>