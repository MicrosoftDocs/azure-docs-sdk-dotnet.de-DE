<Type Name="ComposeDeploymentUpgradeProgress" FullName="System.Fabric.ComposeDeploymentUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class ComposeDeploymentUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ComposeDeploymentUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ComposeDeploymentUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ComposeDeploymentUpgradeProgress" />
  <TypeSignature Language="F#" Value="type ComposeDeploymentUpgradeProgress = class" />
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
      <para>
            Stellt den Verlauf des Upgrade der Bereitstellung verfassen.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Namen der Anwendung aktualisiert werden.</para>
        </summary>
        <value>
          <para>Der Name der Anwendung aktualisiert werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationUnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; ApplicationUnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; ApplicationUnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationUnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationUnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.ApplicationUnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationUnhealthyEvaluations" />
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
          <para>Ruft die auswertungen, die beschreiben den Algorithmus, der vom Integritäts-Manager verwendet werden, um die Integrität der Anwendung, die diese Bereitstellung verfassen auswerten, und die Daten aktualisiert wird. </para>
        </summary>
        <value>
          <para>Die auswertungen, die beschreiben den Algorithmus, der vom Integritäts-Manager verwendet werden, um die Integrität der Anwendung, die diese Bereitstellung verfassen auswerten, und die Daten aktualisiert wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationUpgradeStatusDetails">
      <MemberSignature Language="C#" Value="public string ApplicationUpgradeStatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationUpgradeStatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationUpgradeStatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationUpgradeStatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationUpgradeStatusDetails : string" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.ApplicationUpgradeStatusDetails" />
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
          <para>Ruft die Statusdetails des Anwendungsupgrades einschließlich Fehlermeldung ab. </para>
        </summary>
        <value>
          <para>Die Statusdetails des Anwendungsupgrades, einschließlich der Fehlermeldung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.CurrentUpgradeDomainDuration" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.CurrentUpgradeDomainProgress" />
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
    <Member MemberName="DeploymentName">
      <MemberSignature Language="C#" Value="public string DeploymentName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeploymentName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.DeploymentName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeploymentName As String" />
      <MemberSignature Language="F#" Value="member this.DeploymentName : string" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.DeploymentName" />
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
          <para>Ruft den Namen der zu aktualisierenden Bereitstellung verfassen.</para>
        </summary>
        <value>
          <para>Der Name der zu aktualisierenden Bereitstellung verfassen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureReason">
      <MemberSignature Language="C#" Value="public Nullable&lt;System.Fabric.UpgradeFailureReason&gt; FailureReason { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Fabric.UpgradeFailureReason&gt; FailureReason" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.FailureReason" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.FailureTimestampUtc" />
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
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.NextUpgradeDomain" />
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
          <para>Ruft die nächste upgradedomäne für diese upgradeverlauf ab.</para>
        </summary>
        <value>
          <para>Die nächste upgradedomäne für dieses Upgrade ausgeführt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.StartTimestampUtc" />
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
    <Member MemberName="TargetApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string TargetApplicationTypeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.TargetApplicationTypeVersion" />
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
          <para>Ruft die Version des Anwendungstyps gerade aktualisiert wird.</para>
        </summary>
        <value>
          <para>Die Version des Anwendungstyps gerade aktualisiert wird.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ComposeDeploymentUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="composeDeploymentUpgradeProgress.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der verfassen Bereitstellung upgradefortschritt ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.ComposeDeploymentUpgradeProgress" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDomainProgressAtFailure" />
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
          <para>Die Details der upgradedomäne ausgeführt. <see cref="T:System.Fabric.UpgradeDomainProgress" />(Fixierte Verbindung) festgelegt ist(Fixierte Verbindung) festgelegt ist.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomains">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; UpgradeDomains" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDomains" />
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
          <para>Ruft die Auflistung von upgradedomänen und deren Upgradestatus ab, für das Verfassen bereitstellungsupgrade.</para>
        </summary>
        <value>
          <para>Die Auflistung von upgradedomänen und deren Upgradestatus dafür bilden bereitstellungsupgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeDuration" />
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
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Beschreibung der Richtlinie verwendet wird, für die Aktualisierung dieses bilden Bereitstellung.</para>
        </summary>
        <value>
          <para>Die Beschreibung der Richtlinie für die Aktualisierung dieses verwendet bilden Bereitstellung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeState">
      <MemberSignature Language="C#" Value="public System.Fabric.ComposeDeploymentUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ComposeDeploymentUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As ComposeDeploymentUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.ComposeDeploymentUpgradeState" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ComposeDeploymentUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Gesamtzustand des Upgradevorgangs Bereitstellung verfassen.</para>
        </summary>
        <value>
          <para>Der Gesamtzustand der Bereitstellung Compose-Aktualisierungsprozess.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeStatusDetails">
      <MemberSignature Language="C#" Value="public string UpgradeStatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeStatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeStatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeStatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeStatusDetails : string" Usage="System.Fabric.ComposeDeploymentUpgradeProgress.UpgradeStatusDetails" />
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
          <para>Ruft die Statusdetails bereitstellungsupgrade einschließlich Fehlermeldung zu verfassen. </para>
        </summary>
        <value>
          <para>Die Statusdetails bilden bereitstellungsupgrade, einschließlich der Fehlermeldung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>