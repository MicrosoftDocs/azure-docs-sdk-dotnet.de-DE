<Type Name="RollingUpgradeMode" FullName="System.Fabric.RollingUpgradeMode">
  <TypeSignature Language="C#" Value="public enum RollingUpgradeMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed RollingUpgradeMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.RollingUpgradeMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum RollingUpgradeMode" />
  <TypeSignature Language="F#" Value="type RollingUpgradeMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="49962-101">Gibt den Typ des paralleles Upgrade, bei der Aktualisierung einer Anwendungsinstanz oder -Cluster.</span><span class="sxs-lookup"><span data-stu-id="49962-101">Specifies the type of rolling upgrade when upgrading an application instance or cluster.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="49962-102">Weitere Informationen finden Sie unter Aktualisieren und Skalieren von Service Fabric-Cluster, und Aktualisieren einer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="49962-102">For more information, see Upgrade and Scale a Service Fabric Cluster and Upgrade an Application.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.RollingUpgradeMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="49962-103">Alle Service Fabric-Enumerationen reserviert Ungültiges Flag.</span><span class="sxs-lookup"><span data-stu-id="49962-103">All Service Fabric enumerations have reserved Invalid flag.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Monitored">
      <MemberSignature Language="C#" Value="Monitored" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode Monitored = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberSignature Language="VB.NET" Value="Monitored" />
      <MemberSignature Language="F#" Value="Monitored = 3" Usage="System.Fabric.RollingUpgradeMode.Monitored" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="49962-104">Gibt an, dass das Upgrade überwacht und automatisch erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="49962-104">Specifies that the upgrade should be monitored automatic.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="49962-105">Nach dem Upgrade einer upgradedomäne (UD) wird Service Fabric fahren Sie mit der nächsten UD zu aktualisieren, wenn die Integrität der UD und der Cluster die definierten Integritätsrichtlinien für, dass das Upgrade erfüllt.</span><span class="sxs-lookup"><span data-stu-id="49962-105">After an upgrade domain (UD) is upgraded, Service Fabric will proceed to upgrade the next UD if the health of the UD and the cluster meets the defined health policies for that upgrade.</span></span> <span data-ttu-id="49962-106">Andernfalls wird das gesamte Upgrade als fehlerhaft gekennzeichnet und wird der Fehler beim Aktualisieren der Aktion ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="49962-106">Otherwise, the entire upgrade is marked as failed and the upgrade failure action is taken.</span></span> <span data-ttu-id="49962-107">Die Standardaktion Fehler ist die gesamte Aktualisierung zurücksetzen.</span><span class="sxs-lookup"><span data-stu-id="49962-107">The default failure action is to roll-back the entire upgrade.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredAuto">
      <MemberSignature Language="C#" Value="UnmonitoredAuto" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredAuto = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredAuto" />
      <MemberSignature Language="F#" Value="UnmonitoredAuto = 1" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredAuto" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="49962-108">Gibt an, dass das Upgrade nicht überwacht und automatisch erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="49962-108">Specifies that the upgrade should be unmonitored automatic.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="49962-109">In diesem Modus geht automatisch zur nächste upgradedomäne aktualisieren, bis alle upgradedomänen aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="49962-109">Using this mode,  automatically proceeds to upgrading the next upgrade domain until all upgrade domains are upgraded.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmonitoredManual">
      <MemberSignature Language="C#" Value="UnmonitoredManual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.RollingUpgradeMode UnmonitoredManual = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberSignature Language="VB.NET" Value="UnmonitoredManual" />
      <MemberSignature Language="F#" Value="UnmonitoredManual = 2" Usage="System.Fabric.RollingUpgradeMode.UnmonitoredManual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.RollingUpgradeMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="49962-110">Gibt an, dass das Upgrade nicht überwacht und manuell erfolgen soll.</span><span class="sxs-lookup"><span data-stu-id="49962-110">Specifies that the upgrade should be unmonitored manual.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="49962-111">In diesem Modus muss der Administrator angewiesen, wechseln zur nächsten upgradedomäne (mithilfe der <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> oder <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" /> Methoden) und das Upgrade fortsetzen.</span><span class="sxs-lookup"><span data-stu-id="49962-111">Using this mode, the administrator needs to instruct  to move to the next upgrade domain (using the <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> or <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" /> methods) and continue the upgrade.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>