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
      <para>Stellt eine Klasse zum Kapseln von Parametern, die einen Service Fabric-clusterupgrade Konfiguration beschreibt.</para>
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
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ConfigurationUpgradeDescription" />-Klasse.</para>
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
            Dies ist die Clusterkonfiguration, die angewendet werden, um Cluster.
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
          <para>Ruft ab oder legt die Zeitspanne zwischen den versuchen, eine integritätsprüfung ausführen, wenn die Anwendung oder der Cluster nicht fehlerfrei ist.</para>
        </summary>
        <value>
          <para>Die Länge der Zeit zwischen den versuchen, eine integritätsprüfungen auszuführen wird überprüft, ob die Anwendung oder der Cluster nicht fehlerfrei ist.</para>
        </value>
        <remarks>
          <para>Um eine Wiederholung Systemdiagnose zu verhindern, legen die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> Eigenschaftswert an <see cref="F:System.TimeSpan.Zero" />. Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</para>
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
          <para>Ruft ab oder legt die Länge der Zeit fest, die die Anwendung oder ein Cluster muss fehlerfrei, bevor die integritätsprüfung erfolgreich ist, und das Upgrade durchgeführt, um die nächste Domäne aktualisieren wird.</para>
        </summary>
        <value>
          <para>Die Zeitdauer, dass die Anwendung oder der Cluster fehlerfrei bleiben muss.</para>
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
          <para>Ruft ab oder legt die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Starten des Health Check-Prozesses.</para>
        </summary>
        <value>
          <para>Die Länge der Wartezeit nach Abschluss einer upgradedomäne, bevor der Prozess starten die Integrität überprüft werden.</para>
        </value>
        <remarks>
          <para>Eine unendliche Wartezeit für die integritätsprüfung durchgeführt werden soll, legen die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" /> Eigenschaftswert an <see cref="F:System.TimeSpan.Zero" />. Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</para>
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
          <para>Ruft ab oder legt den maximal zulässigen Prozentsatz Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.
            </para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz der Verringerung der Delta-Integrität. Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</para>
        </value>
        <remarks>Das Delta wird zwischen den Status der Knoten am Anfang des Upgrades und den Status der Knoten zum Zeitpunkt der Integritätsbewertung gemessen. Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet. Der Standardwert ist 10 %.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
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
          <para>Ruft die maximal zulässige Prozentsatz fehlerhafter Anwendungen aus dem <see cref="T:System.Fabric.Health.ClusterHealthPolicy" />.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Anwendungen.</para>
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
          <para>Ruft ab oder legt die maximal zulässigen Prozentsatz fehlerhafter Knoten.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz fehlerhafter Knoten. Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</para>
        </value>
        <remarks>
          <para>
            Der Prozentsatz entspricht dem maximalen tolerierten Prozentsatz an Knoten, die fehlerhaft sein können, bevor der Cluster als fehlerhaft behandelt wird. Wird der Prozentsatz eingehalten, gibt es aber mindestens einen fehlerhaften Knoten, wird die Integrität als „Warning“ ausgewertet.
            Dies wird durch Dividieren der Anzahl der fehlerhaften Knoten über die Gesamtanzahl der Knoten im Cluster berechnet.
            Die Berechnung wird aufgerundet, um einen Fehler auf einer kleinen Anzahl von Knoten zu tolerieren. Standardprozentsatz : null.
            </para>
          <para>Beim Konfigurieren dieses Prozentsatzes muss berücksichtigt werden, dass in großen Clustern immer einige Knoten inaktiv oder aufgrund von Wartungsarbeiten nicht verfügbar sind.</para>
        </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
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
          <para>Ruft ab oder legt die maximal zulässige Prozentsatz upgradedomäne Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.</para>
        </summary>
        <value>
          <para>Die maximal zulässige Prozentsatz upgradedomäne Delta Integrität Beeinträchtigung. Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</para>
        </value>
        <remarks>Das Delta wird zwischen den Status der Upgradedomänenknoten am Anfang des Upgrades und den Status der Upgradedomänenknoten zum Zeitpunkt der Integritätsbewertung gemessen. Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne für alle abgeschlossenen Upgradedomänen durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet. Der Standardwert ist 15 %.</remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para>Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</para>
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
            Ruft eine Zeichenfolgendarstellung der ConfigurationUpgradeDescription ab.
            </summary>
        <returns>Eine Zeichenfolgendarstellung der ConfigurationUpgradeDescription.</returns>
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
          <para>Ruft ab oder legt das Timeout für die upgradedomäne.</para>
        </summary>
        <value>
          <para>Das Timeout für die upgradedomäne.</para>
        </value>
        <remarks>
          <para>Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</para>
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
          <para>Ruft ab oder legt die timeoutgesamtwert für das Upgrade.</para>
        </summary>
        <value>
          <para>Der timeoutgesamtwert für das Upgrade.</para>
        </value>
        <remarks>
          <para>Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>