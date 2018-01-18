<Type Name="ClusterUpgradeHealthPolicy" FullName="System.Fabric.Health.ClusterUpgradeHealthPolicy">
  <TypeSignature Language="C#" Value="public class ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterUpgradeHealthPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterUpgradeHealthPolicy" />
  <TypeSignature Language="F#" Value="type ClusterUpgradeHealthPolicy = class" />
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
      <para><span data-ttu-id="4c9b4-101">Definiert eine Integritätsrichtlinie verwendet, um den Zustand des Clusters zum clusterupgrade bestimmte auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-101">Defines a health policy used to evaluate the health of the cluster specific to cluster upgrade.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="4c9b4-102">Es dient zusammen mit <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> Auswerten der clusterintegrität und ermitteln, ob das überwachte clusterupgrade erfolgreich ist oder ein Rollback ausgeführt werden muss.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-102">It’s used together with <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> to evaluate cluster health and determine whether the monitored cluster upgrade is successful or needs to be rolled back.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterUpgradeHealthPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterUpgradeHealthPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="4c9b4-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-103">Initializes a new instance of the <see cref="T:System.Fabric.Health.ClusterUpgradeHealthPolicy" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentDeltaUnhealthyNodes" />
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
          <para><span data-ttu-id="4c9b4-104">Ruft ab oder legt den maximal zulässigen Prozentsatz Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-104">Gets or sets the maximum allowed percentage of nodes health degradation allowed during cluster upgrades.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="4c9b4-105">Die maximal zulässige Prozentsatz der Verringerung der Delta-Integrität.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-105">The maximum allowed percentage of delta health degradation.</span></span> <span data-ttu-id="4c9b4-106">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-106">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="4c9b4-107">Das Delta wird zwischen den Status der Knoten am Anfang des Upgrades und den Status der Knoten zum Zeitpunkt der Integritätsbewertung gemessen.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-107">The delta is measured between the state of the nodes at the beginning of upgrade and the state of the nodes at the time of the health evaluation.</span></span> <span data-ttu-id="4c9b4-108">Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-108">The check is performed after every upgrade domain upgrade completion to make sure the global state of the cluster is within tolerated limits.</span></span> <span data-ttu-id="4c9b4-109">Der Standardwert ist 10 %.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-109">The default value is 10%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="4c9b4-110">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-110">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MaxPercentUpgradeDomainDeltaUnhealthyNodes">
      <MemberSignature Language="C#" Value="public byte MaxPercentUpgradeDomainDeltaUnhealthyNodes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8 MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxPercentUpgradeDomainDeltaUnhealthyNodes As Byte" />
      <MemberSignature Language="F#" Value="member this.MaxPercentUpgradeDomainDeltaUnhealthyNodes : byte with get, set" Usage="System.Fabric.Health.ClusterUpgradeHealthPolicy.MaxPercentUpgradeDomainDeltaUnhealthyNodes" />
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
          <para><span data-ttu-id="4c9b4-111">Ruft ab oder legt die maximal zulässige Prozentsatz upgradedomäne Knoten Integrität Beeinträchtigung zulässig, während der Cluster-Upgrades.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-111">Gets or sets the maximum allowed percentage of upgrade domain nodes health degradation allowed during cluster upgrades.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="4c9b4-112">Die maximal zulässige Prozentsatz upgradedomäne Delta Integrität Beeinträchtigung.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-112">The maximum allowed percentage of upgrade domain delta health degradation.</span></span> <span data-ttu-id="4c9b4-113">Zulässige Werte sind ganzzahlige Werte von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-113">Allowed values are integer values from zero to 100.</span></span></para>
        </value>
        <remarks><span data-ttu-id="4c9b4-114">Das Delta wird zwischen den Status der Upgradedomänenknoten am Anfang des Upgrades und den Status der Upgradedomänenknoten zum Zeitpunkt der Integritätsbewertung gemessen.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-114">The delta is measured between the state of the upgrade domain nodes at the beginning of upgrade and the state of the upgrade domain nodes at the time of the health evaluation.</span></span> <span data-ttu-id="4c9b4-115">Diese Überprüfung wird nach jedem erfolgreichen Upgrade einer Upgradedomäne für alle abgeschlossenen Upgradedomänen durchgeführt, um sicherzustellen, dass sich der globale Clusterstatus innerhalb eines zulässigen Rahmens befindet.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-115">The check is performed after every upgrade domain upgrade completion for all completed upgrade domains to make sure the state of the upgrade domains is within tolerated limits.</span></span> <span data-ttu-id="4c9b4-116">Der Standardwert ist 15 %.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-116">The default value is 15%.</span></span></remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <para><span data-ttu-id="4c9b4-117">Der angegebene Wert lag außerhalb des Bereichs von ganzzahligen Werten von 0 bis 100.</span><span class="sxs-lookup"><span data-stu-id="4c9b4-117">The specified value was outside the range of integer values from zero to 100.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>