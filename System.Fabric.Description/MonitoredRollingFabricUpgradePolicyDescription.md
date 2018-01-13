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
      <para>Beschreibt das Verhalten beim Ausführen einer Cluster-Upgrades verwenden.</para>
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
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription" />-Klasse.</para>
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
            Abrufen oder Festlegen der Anwendungsintegrität Richtlinien verwendet, um die Integrität von Anwendungen als Teil der integritätsauswertung Cluster ausgewertet werden soll. 
            </summary>
        <value>Die Integritätsrichtlinien für die Anwendung verwendet, um den Zustand des angegebenen auszuwerten.</value>
        <remarks>
          <para>
            Während des Cluster-Upgrades wird die Integrität des Clusters ausgewertet, um festzustellen, ob der Cluster weiterhin fehlerfrei ist. Im Rahmen der integritätsauswertung Cluster sind alle Anwendungen ausgewertet und in den Clusterzustand aggregiert.
            Die Anwendung Integrität Richtlinie Zuordnung wird zum Auswerten der Anwendungen im Rahmen der Auswertung der Cluster verwendet.
            </para>
          <para>
            Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand der betreffenden Anwendung auszuwerten.</para>
          <para>
            Wenn eine Anwendung nicht in der Zuordnung angegeben wird, wird die ApplicationHealthPolicy gefunden, die im Anwendungsmanifest für die Auswertung verwendet werden. </para>
          <para>
            Benutzerdefinierter anwendungsintegritätsrichtlinien werden auch zum Auswerten der clusterintegrität während des Upgrades über <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> oder <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.</para>
          <para>
            Die Zuordnung ist standardmäßig leer.
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
          <para>Ruft ab oder legt ein Flag, das angibt, ob die Delta-Evaluation aktiviert ist.</para>
        </summary>
        <value>
          <para>
            <languageKeyword>"true"</languageKeyword> bei der Delta-integritätsauswertung aktiviert ist; <languageKeyword>"false"</languageKeyword> andernfalls.</para>
        </value>
        <remarks>
          <para>Bei der Delta-Evaluation aktiviert ist, wird sichergestellt, dass die integritätsauswertung für den Cluster, dass die Beeinträchtigung der Integrität Hinsicht-Beschränkung toleriert werden global auf alle Knoten und pro jede upgradedomäne, der ausgewertet wird. Die zulässigen Schwellenwerte werden in angegeben <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />.</para>
          <para>Delta-Auswertung ist standardmäßig deaktiviert.</para>
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
          <para>Abrufen oder festlegen die Integritätsrichtlinie zu verwendende hochleistungsfähiger Integrität für einen Cluster mit einem Upgrade überprüft.</para>
        </summary>
        <value>
          <para>Beim Ausführen der Integrität zu verwendende Integritätsrichtlinie überprüft ein Cluster aktualisieren.</para>
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
          <para>Abrufen oder festlegen die Delta-Integritätsrichtlinie zu verwendende hochleistungsfähiger Integrität für einen Cluster mit einem Upgrade überprüft.</para>
        </summary>
        <value>
          <para>Die Delta-Integritätsrichtlinie beim Ausführen der Integrität zu verwendenden überprüft anhand eines Clusters aktualisieren.</para>
        </value>
        <remarks>
          <para>
            Die Upgrade Integritätsrichtlinie wird verwendet, wenn <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> festgelegt ist, um <languageKeyword>"true"</languageKeyword>. Delta-Auswertung ist standardmäßig deaktiviert.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>