<Type Name="FabricUpgradeProgress" FullName="System.Fabric.FabricUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class FabricUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricUpgradeProgress" />
  <TypeSignature Language="F#" Value="type FabricUpgradeProgress = class" />
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
      <para>Kapselt den Fortschritt einer Service Fabric-Aktualisierung.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainDuration" />
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
          <para>Ruft die geschätzte verstrichene Zeit für die Verarbeitung der aktuellen Domäne zu aktualisieren.</para>
        </summary>
        <value>
          <para>Die geschätzte verstrichene Zeit für die Verarbeitung der aktuellen Domäne zu aktualisieren.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainProgress">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress CurrentUpgradeDomainProgress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.FabricUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Bietet ausführlichen upgradeverlauf für Knoten in der aktuellen upgradedomäne.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.UpgradeDomainProgress" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureReason&gt; FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureReason&gt; FailureReason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.FabricUpgradeProgress.FailureReason" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Fabric.UpgradeFailureReason&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft die Kategorie Upgrade ein Fehler auftritt, wenn Fehler bei der Aktualisierung.
            </para>
        </summary>
        <value>
          <para>Die Kategorie Upgrade ein Fehler auftritt. <see cref="T:System.Fabric.UpgradeFailureReason" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FailureTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FailureTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.FabricUpgradeProgress.FailureTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft den Zeitpunkt, zu dem Fehler bei der Aktualisierung.
            </para>
        </summary>
        <value>
          <para>Der Zeitpunkt, an dem die Aktualisierung (UTC) ist fehlgeschlagen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChangedUpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains (System.Fabric.FabricUpgradeProgress previousProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains(class System.Fabric.FabricUpgradeProgress previousProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.FabricUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChangedUpgradeDomains (previousProgress As FabricUpgradeProgress) As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.GetChangedUpgradeDomains : System.Fabric.FabricUpgradeProgress -&gt; System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="fabricUpgradeProgress.GetChangedUpgradeDomains previousProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousProgress" Type="System.Fabric.FabricUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="previousProgress">
          <para>Der vorherige Statusbericht aus diesen Prozess.</para>
        </param>
        <summary>
          <para>Ruft die Liste der geänderten upgradedomänen ab.</para>
        </summary>
        <returns>
          <para>Die Liste der geänderten upgradedomänen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.FabricUpgradeProgress.NextUpgradeDomain" />
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
          <para>Ruft die nächste upgradedomäne für dieses Upgrade.</para>
        </summary>
        <value>
          <para>Die nächste upgradedomäne für dieses Upgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollingUpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode RollingUpgradeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode RollingUpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.RollingUpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RollingUpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradeMode : System.Fabric.RollingUpgradeMode" Usage="System.Fabric.FabricUpgradeProgress.RollingUpgradeMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Modus der für parallele Upgrade für dieses Upgrade.</para>
        </summary>
        <value>
          <para>Der Modus für parallele Upgrades für dieses Upgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.FabricUpgradeProgress.StartTimestampUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft den Zeitpunkt, zu dem das Upgrade begonnen hat.
            </para>
        </summary>
        <value>
          <para>Der Zeitpunkt, zu dem das Upgrade in UTC begonnen hat.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetCodeVersion">
      <MemberSignature Language="C#" Value="public string TargetCodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetCodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.TargetCodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetCodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetCodeVersion : string" Usage="System.Fabric.FabricUpgradeProgress.TargetCodeVersion" />
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
          <para>Ruft die Version des Zielservers Code für dieses Upgrade.</para>
        </summary>
        <value>
          <para>Die Zielversion des Code für dieses Upgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetConfigVersion">
      <MemberSignature Language="C#" Value="public string TargetConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.TargetConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetConfigVersion : string" Usage="System.Fabric.FabricUpgradeProgress.TargetConfigVersion" />
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
          <para>Ruft die Version des Zielservers-Konfiguration für dieses Upgrade.</para>
        </summary>
        <value>
          <para>Die Zielversion des Konfiguration für dieses Upgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="fabricUpgradeProgress.ToString " />
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
            Ruft eine Zeichenfolgendarstellung für den Fortschritt der Fabric-Aktualisierung ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.FabricUpgradeProgress" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.FabricUpgradeProgress.UnhealthyEvaluations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die integritätsauswertungen, in denen beschrieben wird, die Daten und des vom Integritäts-Manager zum Auswerten der clusterintegrität verwendeten Algorithmus ab. Nur aufgefüllt, wenn der Cluster aggregiert des Integritätsstatus ist <see cref="F:System.Fabric.Health.HealthState.Error" />. Das Upgrade aufgrund einer integritätsauswertung ein Rollback ausgeführt, stellt eine Ansicht der Momentaufnahme des Zustands bereit, zum Zeitpunkt der Systemdiagnose durchgeführt wurde.</para>
        </summary>
        <value>
          <para>Die fehlerhaften auswertungen, die dem aktuellen aggregierte Integritätsstatus geführt hat. Die Elemente in der Liste der folgenden Typen sein können: <see cref="T:System.Fabric.Health.ApplicationsHealthEvaluation" />, <see cref="T:System.Fabric.Health.NodesHealthEvaluation" />, <see cref="T:System.Fabric.Health.UpgradeDomainNodesHealthEvaluation" />, <see cref="T:System.Fabric.Health.SystemApplicationHealthEvaluation" /> Oror <see cref="T:System.Fabric.Health.EventHealthEvaluation" />.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.FabricUpgradeDescription UpgradeDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.FabricUpgradeDescription UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDescription As FabricUpgradeDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : System.Fabric.Description.FabricUpgradeDescription" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.FabricUpgradeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Aktualisierungsparameter-Details, die das Verhalten des aktuellen Upgrade beschreiben.</para>
        </summary>
        <value>
          <para>Die Parameterdetails der Upgrade-, die das Verhalten des aktuellen Upgrade beschreiben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeDomainProgress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            Ruft strukturierte Informationen, welche Aktionen vom System zum Zeitpunkt der Upgradefehler durchgeführt wurden.
            </para>
        </summary>
        <value>
          <para>Die Details zum upgradeverlauf. <see cref="T:System.Fabric.UpgradeDomainProgress" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Liste der zu aktualisierenden Domänen ab.</para>
        </summary>
        <value>
          <para>Die Liste der zu aktualisierenden Domänen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.FabricUpgradeProgress.UpgradeDuration" />
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
          <para>Ruft die geschätzte verstrichene Zeit für die Verarbeitung von des aktuellen insgesamt aktualisieren.</para>
        </summary>
        <value>
          <para>Die geschätzte verstrichene Zeit für die Verarbeitung des gesamten aktuellen Upgrades.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.FabricUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As FabricUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.FabricUpgradeState" Usage="System.Fabric.FabricUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Upgradestatus für dieses Upgrade.</para>
        </summary>
        <value>
          <para>Der Upgradestatus für dieses Upgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>