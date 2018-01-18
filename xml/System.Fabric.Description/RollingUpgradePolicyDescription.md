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
      <para><span data-ttu-id="7741f-101">Beschreibung der Richtlinie für paralleles Upgrade.</span><span class="sxs-lookup"><span data-stu-id="7741f-101">Description of the rolling upgrade policy.</span></span></para>
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
          <para><span data-ttu-id="7741f-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7741f-102">Initializes a new instance of the <see cref="T:System.Fabric.Description.RollingUpgradePolicyDescription" /> class.</span></span></para>
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
          <para><span data-ttu-id="7741f-103">Gibt an, ob der Diensthost neu gestartet werden soll, auch wenn keine Änderungen am Code-Paket als Teil des Upgrades sind.</span><span class="sxs-lookup"><span data-stu-id="7741f-103">Specifies if the service host should be restarted even when there are no code package changes as part of the upgrade.</span></span> <span data-ttu-id="7741f-104">Legen Sie dieses Flag auf "true", wenn den Dienst kann keine Daten oder Config paketänderungen dynamisch akzeptieren.</span><span class="sxs-lookup"><span data-stu-id="7741f-104">Set this flag to true if the service cannot dynamically accept config or data package changes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7741f-105">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7741f-105">Returns <see cref="T:System.Boolean" />.</span></span></para>
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
          <para><span data-ttu-id="7741f-106">Typ: <see cref="T:System.Fabric.RollingUpgradeMode" />gibt die Typen der Aktualisierung (<see cref="T:System.Fabric.RollingUpgradeMode" />) zum Aktualisieren der Anwendungsinstanz verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="7741f-106">Type: <see cref="T:System.Fabric.RollingUpgradeMode" />Specifies the types of upgrade (<see cref="T:System.Fabric.RollingUpgradeMode" />) to be used for upgrading the application instance.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="7741f-107">Gibt <see cref="T:System.Fabric.RollingUpgradeMode" />zurück.</span><span class="sxs-lookup"><span data-stu-id="7741f-107">Returns <see cref="T:System.Fabric.RollingUpgradeMode" />.</span></span></para>
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
          <para><span data-ttu-id="7741f-108">Gibt die Dauer, die Service Fabric warten soll, vor dem Upgrade die Dienste einer Anwendung-Instanz in einer upgradedomäne, wenn die Dienste nicht Quorum verfügen.</span><span class="sxs-lookup"><span data-stu-id="7741f-108">Specifies the duration Service Fabric should wait before upgrading the services of an application instance in an upgrade domain if the services do not have quorum.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="7741f-109">Die Dauer sollte Service Fabric warten Sie vor dem Upgrade die Dienste einer Anwendung-Instanz in einer upgradedomäne, wenn die Dienste nicht Quorum verfügen.</span><span class="sxs-lookup"><span data-stu-id="7741f-109">The duration Service Fabric should wait before upgrading the services of an application instance in an upgrade domain if the services do not have quorum.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>