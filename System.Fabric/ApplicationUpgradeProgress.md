<Type Name="ApplicationUpgradeProgress" FullName="System.Fabric.ApplicationUpgradeProgress">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ApplicationUpgradeProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeProgress" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeProgress = class" />
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
            Stellt den Upgradestatus der Anwendungsinstanz.
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationName" />
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
    <Member MemberName="ApplicationTypeName">
      <MemberSignature Language="C#" Value="public string ApplicationTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeName : string" Usage="System.Fabric.ApplicationUpgradeProgress.ApplicationTypeName" />
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
          <para>Ruft den Typnamen der zu aktualisierenden Anwendung ab.</para>
        </summary>
        <value>
          <para>Der Typname der Anwendung aktualisiert werden.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentUpgradeDomainDuration">
      <MemberSignature Language="C#" Value="public TimeSpan CurrentUpgradeDomainDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan CurrentUpgradeDomainDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainDuration" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentUpgradeDomainProgress As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.CurrentUpgradeDomainProgress : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.CurrentUpgradeDomainProgress" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureReason" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureReason As Nullable(Of UpgradeFailureReason)" />
      <MemberSignature Language="F#" Value="member this.FailureReason : Nullable&lt;System.Fabric.UpgradeFailureReason&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureReason" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FailureTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.FailureTimestampUtc" />
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
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains (System.Fabric.ApplicationUpgradeProgress previousProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class System.Fabric.UpgradeDomainStatus&gt; GetChangedUpgradeDomains(class System.Fabric.ApplicationUpgradeProgress previousProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChangedUpgradeDomains (previousProgress As ApplicationUpgradeProgress) As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.GetChangedUpgradeDomains : System.Fabric.ApplicationUpgradeProgress -&gt; System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="applicationUpgradeProgress.GetChangedUpgradeDomains previousProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="previousProgress" Type="System.Fabric.ApplicationUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="previousProgress">
          <para>Der vorherige <see cref="T:System.Fabric.ApplicationUpgradeProgress" /> Objekt.</para>
        </param>
        <summary>
          <para>Gibt eine Hilfsmethode, die eine Auflistung der zu aktualisierenden Domänen, die geändert wurden zurückgibt in die <see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" /> Zustand oder die <see cref="F:System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" /> Status seit der <see cref="M:System.Fabric.ApplicationUpgradeProgress.GetChangedUpgradeDomains(System.Fabric.ApplicationUpgradeProgress)" /> Methode wurde aufgerufen.</para>
        </summary>
        <returns>
          <para>Eine Hilfsmethode, die eine Auflistung von upgradedomänen zurückgibt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentException">
          <para>Den Anwendungsnamen oder den Anwendungstyp, der die <paramref name="previousProgress" /> Parameter entspricht nicht den Anwendungsnamen oder den Anwendungstyp dieses Objekts.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="NextUpgradeDomain">
      <MemberSignature Language="C#" Value="public string NextUpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextUpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextUpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.NextUpgradeDomain : string" Usage="System.Fabric.ApplicationUpgradeProgress.NextUpgradeDomain" />
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
    <Member MemberName="RollingUpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode RollingUpgradeMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode RollingUpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RollingUpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.RollingUpgradeMode : System.Fabric.RollingUpgradeMode" Usage="System.Fabric.ApplicationUpgradeProgress.RollingUpgradeMode" />
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
          <para>Ruft den Modus der für parallele Upgrade für dieses Upgrade ausgeführt.</para>
        </summary>
        <value>
          <para>Der Modus für parallele Upgrades für dieses Upgrade ausgeführt.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTimestampUtc">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTimestampUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTimestampUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTimestampUtc As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTimestampUtc : Nullable&lt;DateTime&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.StartTimestampUtc" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string" Usage="System.Fabric.ApplicationUpgradeProgress.TargetApplicationTypeVersion" />
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
      <MemberSignature Language="DocId" Value="M:System.Fabric.ApplicationUpgradeProgress.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationUpgradeProgress.ToString " />
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
            Ruft eine Zeichenfolgendarstellung der upgradeverlaufs einer Anwendung ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung des <see cref="T:System.Fabric.ApplicationUpgradeProgress" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnhealthyEvaluations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.HealthEvaluation&gt; UnhealthyEvaluations" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnhealthyEvaluations As IList(Of HealthEvaluation)" />
      <MemberSignature Language="F#" Value="member this.UnhealthyEvaluations : System.Collections.Generic.IList&lt;System.Fabric.Health.HealthEvaluation&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UnhealthyEvaluations" />
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
          <para>Ruft die auswertungen für die beschreiben, die die Daten und des vom Integritäts-Manager zum Auswerten der Anwendungsintegrität verwendeten Algorithmus ab. </para>
        </summary>
        <value>
          <para>Die auswertungen die beschreiben, die die Daten und den Algorithmus, der vom Integritäts-Manager verwendet werden, um den Anwendungszustand auszuwerten.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ApplicationUpgradeDescription UpgradeDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDescription As ApplicationUpgradeDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradeDescription : System.Fabric.Description.ApplicationUpgradeDescription" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ApplicationUpgradeDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Parameter, die das Verhalten des aktuellen Upgrade beschreiben.</para>
        </summary>
        <value>
          <para>Die Parameter, die das Verhalten des aktuellen Upgrade beschreiben.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainProgressAtFailure">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.UpgradeDomainProgress UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainProgressAtFailure As UpgradeDomainProgress" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainProgressAtFailure : System.Fabric.UpgradeDomainProgress" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomainProgressAtFailure" />
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
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomains As ReadOnlyCollection(Of UpgradeDomainStatus)" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomains : System.Collections.ObjectModel.ReadOnlyCollection&lt;System.Fabric.UpgradeDomainStatus&gt;" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDomains" />
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
          <para>Ruft die Auflistung von upgradedomänen und deren Upgradestatus für das Anwendungsupgrade ab.</para>
        </summary>
        <value>
          <para>Die Auflistung der upgradedomänen und deren Upgradestatus für das Anwendungsupgrade.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDuration">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDuration : TimeSpan" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeDuration" />
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
      <MemberSignature Language="C#" Value="public System.Fabric.ApplicationUpgradeState UpgradeState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.ApplicationUpgradeState UpgradeState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeState As ApplicationUpgradeState" />
      <MemberSignature Language="F#" Value="member this.UpgradeState : System.Fabric.ApplicationUpgradeState" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft den Gesamtzustand des Upgradevorgangs Anwendung ab.</para>
        </summary>
        <value>
          <para>Upgradeprozess für der Gesamtzustand der Anwendung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeStatusDetails">
      <MemberSignature Language="C#" Value="public string UpgradeStatusDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeStatusDetails" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeStatusDetails As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeStatusDetails : string" Usage="System.Fabric.ApplicationUpgradeProgress.UpgradeStatusDetails" />
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
          <para>Ruft die Statusdetails des Upgrades, einschließlich der Fehlermeldung ab. </para>
        </summary>
        <value>
          <para>Die Statusdetails des Upgrades, einschließlich der Fehlermeldung.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>