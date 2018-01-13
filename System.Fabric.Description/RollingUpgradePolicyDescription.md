<Type Name="RollingUpgradePolicyDescription" FullName="System.Fabric.Description.RollingUpgradePolicyDescription">
  <TypeSignature Language="C#" Value="public class RollingUpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RollingUpgradePolicyDescription extends System.Fabric.Description.UpgradePolicyDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.RollingUpgradePolicyDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class RollingUpgradePolicyDescription&#xA;Inherits UpgradePolicyDescription" />
  <TypeSignature Language="F#" Value="type RollingUpgradePolicyDescription = class&#xA;    inherit UpgradePolicyDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.UpgradePolicyDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Beschreibung der Richtlinie für paralleles Upgrade.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RollingUpgradePolicyDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.RollingUpgradePolicyDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para>Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" />-Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ForceRestart">
      <MemberSignature Language="C#" Value="public bool ForceRestart { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForceRestart" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />
      <MemberSignature Language="VB.NET" Value="Public Property ForceRestart As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForceRestart : bool with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.ForceRestart" />
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
          <para>Gibt an, ob der Diensthost neu gestartet werden soll, auch wenn keine Änderungen am Code-Paket als Teil des Upgrades sind. Legen Sie dieses Flag auf "true", wenn den Dienst kann keine Daten oder Config paketänderungen dynamisch akzeptieren.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Boolean" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeMode">
      <MemberSignature Language="C#" Value="public System.Fabric.RollingUpgradeMode UpgradeMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.RollingUpgradeMode UpgradeMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeMode As RollingUpgradeMode" />
      <MemberSignature Language="F#" Value="member this.UpgradeMode : System.Fabric.RollingUpgradeMode with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeMode" />
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
          <para>Typ: <see cref="T:System.Fabric.RollingUpgradeMode" />gibt die Typen der Aktualisierung (<see cref="T:System.Fabric.RollingUpgradeMode" />) zum Aktualisieren der Anwendungsinstanz verwendet werden soll. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.RollingUpgradeMode" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeReplicaSetCheckTimeout">
      <MemberSignature Language="C#" Value="public TimeSpan UpgradeReplicaSetCheckTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeReplicaSetCheckTimeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UpgradeReplicaSetCheckTimeout : TimeSpan with get, set" Usage="System.Fabric.Description.RollingUpgradePolicyDescription.UpgradeReplicaSetCheckTimeout" />
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
          <para>Gibt die Dauer, die Service Fabric warten soll, vor dem Upgrade die Dienste einer Anwendung-Instanz in einer upgradedomäne, wenn die Dienste nicht Quorum verfügen.</para>
        </summary>
        <value>
          <para>Die Dauer sollte Service Fabric warten Sie vor dem Upgrade die Dienste einer Anwendung-Instanz in einer upgradedomäne, wenn die Dienste nicht Quorum verfügen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>