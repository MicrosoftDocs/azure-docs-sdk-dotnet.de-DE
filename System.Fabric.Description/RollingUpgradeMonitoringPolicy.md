<Type Name="RollingUpgradeMonitoringPolicy" FullName="System.Fabric.Description.RollingUpgradeMonitoringPolicy">
  <TypeSignature Language="C#" Value="public class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradeMonitoringPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradeMonitoringPolicy" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMonitoringPolicy = class" />
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
      <para>Stellt eine Klasse, ein paralleles Upgrade Überwachen der Richtlinie zu kapseln.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradeMonitoringPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradeMonitoringPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" />-Klasse.</para>
        </summary>
        <remarks>
          <para>Die Initialisierung legt die Eigenschaften der <see cref="T:System.Fabric.Description.RollingUpgradeMonitoringPolicy" /> Klasse mit den folgenden Standardeinstellungen.</para>
          <para>Eigenschaft</para>
          <para>Standardwert</para>
          <list type="table">
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />
                </para>
                <para>Dieser Wert geändert werden muss oder eine <see cref="T:System.ArgumentException" /> wird vor Beginn des Upgrades ausgelöst werden.</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="F:System.TimeSpan.Zero" />
                </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
                </para>
              </term>
              <description>
                <para>
                  <see cref="T:System.TimeSpan" />Wert, der standardmäßig auf 120 Sekunden.
                    </para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
                </para>
              </term>
              <description>
                <para>600 Sekunden</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
                </para>
              </term>
              <description>
                <para>TimeSpan.FromSeconds ("uint". "MaxValue")</para>
              </description>
            </item>
            <item>
              <term>
                <para>
                  <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
                </para>
              </term>
              <description>
                <para>TimeSpan.FromSeconds ("uint". "MaxValue")</para>
              </description>
            </item>
          </list>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureAction">
      <MemberSignature Language="C#" Value="public System.Fabric.UpgradeFailureAction FailureAction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.UpgradeFailureAction FailureAction" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureAction As UpgradeFailureAction" />
      <MemberSignature Language="F#" Value="member this.FailureAction : System.Fabric.UpgradeFailureAction with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die Aktion an, wenn das Upgrade fehlschlägt. Der Standardwert lautet <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" />.</para>
        </summary>
        <value>
          <para>Die Aktion an, wenn das Upgrade fehlschlägt.</para>
        </value>
        <remarks>
          <para>Die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> -Eigenschaft muss geändert werden, von der Standardeinstellung <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> oder ein <see cref="T:System.ArgumentException" /> wird vor Beginn des Upgrades ausgelöst werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentException">
          <para>Die <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" />-Eigenschaft ist auf <see cref="F:System.Fabric.UpgradeFailureAction.Invalid" /> festgelegt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckRetryTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckRetryTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckRetryTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" />
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
          <para>Ruft ab oder legt die Länge der Zeit, die Integrität kann fehlschlagen überprüft, fortlaufend, bevor das Upgrade fehlschlägt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</para>
        </summary>
        <value>
          <para>Die Zeitdauer, die integritätsprüfungen fortlaufend ausgeführt werden können.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 600 Sekunden. Festlegen von <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckRetryTimeout" /> zu <see cref="F:System.TimeSpan.Zero" /> führt dazu, nur einen einzelnen integritätsprüfung durchgeführt werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckStableDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckStableDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckStableDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckStableDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckStableDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckStableDuration" />
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
          <para>Ruft ab oder legt die Zeitspanne, die Integrität erfüllen muss überprüft, fortlaufend, bevor das Upgrade auf die nächste upgradedomäne durchgeführt wird.</para>
        </summary>
        <value>
          <para>Die Zeitdauer, die fortlaufend Systemdiagnosen übergeben müssen.</para>
        </value>
        <remarks>
          <para>Der Standardwert ist 120 Sekunden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthCheckWaitDuration">
      <MemberSignature Language="C#" Value="public TimeSpan HealthCheckWaitDuration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan HealthCheckWaitDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthCheckWaitDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.HealthCheckWaitDuration : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.HealthCheckWaitDuration" />
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
          <para>Ruft ab oder legt die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Ausführen von integritätsprüfungen fest.</para>
        </summary>
        <value>
          <para>Die Länge der Wartezeit nach Abschluss einer upgradedomäne vor dem Ausführen von integritätsprüfungen.</para>
        </value>
        <remarks>
          <para>Der Standardwert lautet <see cref="F:System.TimeSpan.Zero" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeDomainTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeDomainTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeDomainTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeDomainTimeout" />
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
          <para>Ruft ab oder legt die Länge der Zeit, die die Verarbeitung von keine der upgradedomänen vor dem Upgrade ein Fehler auftritt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</para>
        </summary>
        <value>
          <para>Das Timeout für keine der upgradedomänen.</para>
        </value>
        <remarks>
          <para>Die Standardeinstellung ist TimeSpan.FromSeconds ("uint". "MaxValue").</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradeMonitoringPolicy.UpgradeTimeout" />
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
          <para>Ruft ab oder legt die Länge der Zeit, die das gesamte Upgrade vor dem Upgrade ein Fehler auftritt und die angegebene Aktion <see cref="P:System.Fabric.Description.RollingUpgradeMonitoringPolicy.FailureAction" /> auftritt.</para>
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