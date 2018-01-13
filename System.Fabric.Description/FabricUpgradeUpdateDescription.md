<Type Name="FabricUpgradeUpdateDescription" FullName="System.Fabric.Description.FabricUpgradeUpdateDescription">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeUpdateDescription : System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeUpdateDescription extends System.Fabric.Description.UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeUpdateDescription&#xA;Inherits UpgradeUpdateDescriptionBase" />
  <TypeSignature Language="F#" Value="type FabricUpgradeUpdateDescription = class&#xA;    inherit UpgradeUpdateDescriptionBase" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradeUpdateDescriptionBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>So ändern Sie die Upgrade-Parameter, beschreibt das Verhalten Cluster-Upgrades verwendet.
            Weitere Informationen finden Sie unter <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricUpgradeUpdateDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.FabricUpgradeUpdateDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt eine Instanz der <see cref="T:System.Fabric.Description.FabricUpgradeUpdateDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.ApplicationHealthPolicyMap" />
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
            Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand der betreffenden Anwendung auszuwerten.
            </para>
          <para>
            Wenn eine Anwendung nicht in der Zuordnung angegeben wird, wird die ApplicationHealthPolicy gefunden, die im Anwendungsmanifest für die Auswertung verwendet werden. </para>
          <para>
            Benutzerdefinierter anwendungsintegritätsrichtlinien werden auch zum Auswerten der clusterintegrität während des Upgrades über <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" /> oder <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthChunkAsync(System.Fabric.Description.ClusterHealthChunkQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />.
            </para>
          <para>
            Die Zuordnung wird null als Standardwert, was bedeutet, dass das Update nicht zutrifft, um zuvor anwendungsintegritätsrichtlinien festzulegen.
            Um die Anwendung-Integritätsrichtlinien zu aktualisieren, Erstellen der Zuordnung zuerst, dann fügen Sie Einträge für die gewünschten Anwendungen an.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDeltaHealthEvaluation">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableDeltaHealthEvaluation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableDeltaHealthEvaluation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDeltaHealthEvaluation As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableDeltaHealthEvaluation : Nullable&lt;bool&gt; with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.HealthPolicy" />
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
          <para>Ruft den <see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.HealthPolicy" /> ab oder legt diesen fest.</para>
        </summary>
        <value>
          <para>Die clusterintegritätsrichtlinie, die zum Auswerten der clusterintegrität während des Upgrades verwendet wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeHealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterUpgradeHealthPolicy UpgradeHealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeHealthPolicy As ClusterUpgradeHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.UpgradeHealthPolicy : System.Fabric.Health.ClusterUpgradeHealthPolicy with get, set" Usage="System.Fabric.Description.FabricUpgradeUpdateDescription.UpgradeHealthPolicy" />
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
          <para>Ruft den <see cref="P:System.Fabric.Description.MonitoredRollingFabricUpgradePolicyDescription.UpgradeHealthPolicy" /> ab oder legt diesen fest.</para>
        </summary>
        <value>
          <para>Integritätsrichtlinie, die zum Auswerten der clusterintegrität während des Upgrades verwendet, die den Cluster aktualisieren.</para>
        </value>
        <remarks>
          <para>
            Die Upgrade Integritätsrichtlinie wird verwendet, wenn <see cref="P:System.Fabric.Description.FabricUpgradeUpdateDescription.EnableDeltaHealthEvaluation" /> festgelegt ist, um <languageKeyword>"true"</languageKeyword>. Die Delta-Auswertung ist standardmäßig deaktiviert.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>